# AGENTS.md

Short, agent-operational guide. See [CLAUDE.md](CLAUDE.md) for project history and fix log.

## What this repo is

An iSamples earth-science metadata profile. Pipeline: SKOS Turtle (`vocabulary/*.ttl`) → SQLite via `tools/vocab.py` (navocab) → Markdown via `tools/vocab2mdCacheV2.py` → HTML via Quarto. Runs in Docker as a GitHub Action (`action.yml`, `.github/workflows/process_vocab.yml`).

Landing page: <http://isamples.org/metadata_profile_earth_science/> (served from `gh-pages/docs`, generated from `docs/readme.md`).

## Vocabularies

| Slug (no ext) | ConceptScheme CURIE |
|---|---|
| `earthenv_material_extension_mineral_group` | `ming:mineralgroupvocabulary` |
| `earthenv_material_extension_rock_sediment` | `rksd:rocksedimentvocabulary` |
| `earthenv_sampled_feature_role` | `essampledfeatrole:sfrolevocabulary` |
| `earthenv_materialsampleobject_type` | `esmat:essampletype` |

## Local verification (Option A — no Docker)

Fastest feedback loop. Exercises all the pure-Python fixes but not the Dockerfile pin.

```bash
python -m venv .venv
.venv/Scripts/python.exe -m pip install -r tools/requirements.txt

# Loop through every vocab
declare -a pairs=(
  "earthenv_material_extension_mineral_group ming:mineralgroupvocabulary"
  "earthenv_material_extension_rock_sediment rksd:rocksedimentvocabulary"
  "earthenv_sampled_feature_role essampledfeatrole:sfrolevocabulary"
  "earthenv_materialsampleobject_type esmat:essampletype"
)
mkdir -p testoutput/local_run
for p in "${pairs[@]}"; do
  read -r V U <<< "$p"
  rm -f cache/vocabularies.db
  .venv/Scripts/python.exe tools/vocab.py --verbosity ERROR -s cache/vocabularies.db load "vocabulary/$V.ttl" "$U" || continue
  .venv/Scripts/python.exe tools/vocab2mdCacheV2.py cache/vocabularies.db "$U" > "testoutput/local_run/$V.md" && \
    quarto render "testoutput/local_run/$V.md" -t html
done
```

Compare `testoutput/local_run/*.html` against the committed `testoutput/*.html` for sanity.

## Docker verification (Option B — matches the action)

```bash
docker build -t earth-sci-vocab .
docker run --rm \
  -e INPUT_ACTION=docs \
  -e INPUT_PATH=/app \
  -e INPUT_INPUTTTL='earthenv_material_extension_mineral_group|earthenv_material_extension_rock_sediment|earthenv_sampled_feature_role|earthenv_materialsampleobject_type' \
  -e INPUT_INPUTVOCABURI='ming:mineralgroupvocabulary|rksd:rocksedimentvocabulary|essampledfeatrole:sfrolevocabulary|esmat:essampletype' \
  -v "/$(pwd)/docs://app/docs" \
  earth-sci-vocab
```

The `//` prefix on the volume path is a Git-Bash-on-Windows workaround; drop it on Linux/macOS.

## Do not touch

- `.idea/workspace.xml`, `vocabulary/.project` — JetBrains / Eclipse IDE state.
- Any `*-SMR-Samsung.*` files — owner's local experiments.
- Pre-existing staged or pending deletions you didn't introduce — leave them for the owner to commit separately.

## Common fix pattern (for porting to sibling repos)

This codebase descends from `isamplesorg/vocabularyTemplate`. The 2026-04-22 fix set (see CLAUDE.md for per-file detail):

1. `Dockerfile` — pin `FROM python:3.12-slim` (3-slim → 3.14 drops `pkg_resources`).
2. `tools/requirements.txt` — add `setuptools<81`.
3. Remove any stale `cache/vocabularies-*.db` files.
4. `.github/workflows/process_vocab.yml` — verify every slug in `inputttl` matches an actual `vocabulary/*.ttl`; verify deploy `branch:` target is `gh-pages` (not a stale feature branch).
5. `.github/actions/github_action_main.py` — reset cache DB per vocab, process load+md+render in a single per-vocab loop, use `enumerate` not a shared `theindex`.
6. `tools/vocab2mdCacheV2.py` — `getVocabRoot` UNIONs `skos:topConceptOf` + `skos:hasTopConcept`; `getNarrower` falls back to unscoped `skos:broader` when `skos:inScheme` is absent.
7. `tools/navocab/__init__.py::purge_store` — stop referencing undefined `graph`; log + defer to external file deletion.

Applied and verified in: earth_science, archaeology, biology. GeoSamples/`vocabularies` repo (at `../vocabularies`) still had items 1-2 unfixed as of 2026-04-22.

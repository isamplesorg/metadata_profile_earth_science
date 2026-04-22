# CLAUDE.md

## Project overview

This repository contains SKOS vocabularies (RDF/Turtle) for iSamples Earth Science metadata profiles. It also functions as a GitHub Action that converts SKOS Turtle files to HTML documentation via a pipeline: Turtle → SQLite (navocab) → Markdown (vocab2mdCacheV2) → HTML (Quarto).

GitHub Pages landing page: <http://isamples.org/metadata_profile_earth_science/> — rendered from `docs/readme.md`, deployed from the `gh-pages` branch under `/docs`. `https://isamplesorg.github.io/metadata_profile_earth_science/` 301-redirects to the `isamples.org` URL.

## Repository structure

- `vocabulary/` — Source SKOS Turtle (.ttl) files
- `tools/` — Python processing tools (vocab.py, vocab2mdCacheV2.py, navocab/)
- `docs/` — Generated HTML/Markdown output (deployed to gh-pages)
- `cache/` — SQLite database directory (should be transient)
- `.github/actions/github_action_main.py` — Docker entrypoint for the pipeline
- `.github/workflows/` — GitHub Actions workflow definitions
- `Dockerfile` — Processing container, pinned to `python:3.12-slim`
- `action.yml` — GitHub Action metadata

## Vocabularies

| File | ConceptScheme CURIE |
|------|-------------------|
| `earthenv_material_extension_mineral_group.ttl` | `ming:mineralgroupvocabulary` |
| `earthenv_material_extension_rock_sediment.ttl` | `rksd:rocksedimentvocabulary` |
| `earthenv_materialsampleobject_type.ttl` | `esmat:essampletype` |
| `earthenv_sampled_feature_role.ttl` | `essampledfeatrole:sfrolevocabulary` |

## Pipeline fixes applied 2026-04-22 (commit 5a42470)

This repo shares the same codebase as GeoSamples/vocabularies (both from isamplesorg/vocabularyTemplate). The following fixes were ported here and verified with a local Option-A run against all four vocabs (load/md/render all exit 0):

1. **Dockerfile**: pinned to `python:3.12-slim` so `pkg_resources` remains available (Python 3.14 drops it).
2. **tools/requirements.txt**: added `setuptools<81` (rdflib-sqlalchemy needs `pkg_resources`).
3. **Stale cache DB**: removed `cache/vocabularies-SMR-Samsung.db` (was 6.5MB, untracked).
4. **Workflow filename**: `process_vocab.yml` now references `earthenv_materialsampleobject_type` (was the nonexistent `earthenv_specimen_type`).
5. **github_action_main.py**: resets the cache DB before each vocabulary (fresh DB per vocab, no cross-vocab pollution); fixed the `theindex=0`-inside-loop bug.
6. **vocab2mdCacheV2.py**: `getVocabRoot` now UNIONs `skos:topConceptOf` and `skos:hasTopConcept`; `getNarrower` falls back to an unscoped `skos:broader` query when concepts omit `skos:inScheme`.
7. **navocab.purge_store**: no longer crashes on undefined `graph` local; logs a warning and defers to external file deletion.

The sibling GeoSamples/vocabularies repo (at `../vocabularies`) still has the unfixed versions of (1) and (2) as of this date — consider porting back if you work there next.

## GitHub Actions workflows

- **Process vocabularies** (`process_vocab.yml`) — Manual dispatch. Processes all 4 vocabularies.
- **Process SESAR vocab** (`process_sesar_vocab.yml`) — Manual dispatch. Processes SESAR rock/sediment extension.
- **Test docs** (`testdocs_process_vocab.yml`) — Manual dispatch. Test workflow.
- **Test JSON** (`testjson_process_vocab.yml`) — Manual dispatch. JSON generation test.

## Processing pipeline

Same as GeoSamples/vocabularies:
1. `vocab.py load <file.ttl> <conceptscheme-uri>` — parse Turtle, store in SQLite
2. `vocab2mdCacheV2.py <db> <conceptscheme-uri>` — query DB, generate Markdown
3. `quarto render <file.md> -t html` — render Markdown to HTML
4. Deploy HTML to gh-pages via JamesIves/github-pages-deploy-action

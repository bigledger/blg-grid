# Upstream

blg-grid is a fork of AG Grid Community. This file records where the forked code came from and every upstream change taken since.

## Source

| | |
| --- | --- |
| Repository | https://github.com/ag-grid/ag-grid |
| Tag | `b31.3.4` |
| Commit | `b632ff58db83fd24454dd027a676541581645c4b` |
| Imported | 2026-11-12 |

## Folders taken

All MIT licensed (checked in each folder's `package.json` and `LICENSE.txt`). Paths are kept the same as upstream, so an upstream diff applies directly.

| Folder | Upstream package |
| --- | --- |
| `community-modules/core` | `@ag-grid-community/core` |
| `community-modules/client-side-row-model` | `@ag-grid-community/client-side-row-model` |
| `community-modules/infinite-row-model` | `@ag-grid-community/infinite-row-model` |
| `community-modules/csv-export` | `@ag-grid-community/csv-export` |
| `community-modules/styles` | `@ag-grid-community/styles` |
| `community-modules/angular` | `@ag-grid-community/angular` |

## Left out

- `dist/` folders: build output committed in the release tag. We build from source.
- `github-banner.png`, `github-grid-demo.jpg`: AG Grid branding.
- `community-modules/react`, `vue`, `vue3`: not needed.
- `enterprise-modules/`: commercially licensed. **Never copy from it, from any version.**

## Changes to forked files

The first import commit is the untouched upstream copy. Every later change to a forked file is marked with a `// blg:` comment where possible, so the list of edited files can be produced with `git grep "blg:"`.

## Upstream changes taken

None yet.

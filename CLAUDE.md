# Working in this repo

## Build artifacts

`assets/dist/` and `dist/` are gitignored (see `.gitignore`) — they're built by
`npm run build` / `gulp`. Only source files (`assets/css/**`, `assets/js/**`,
`*.hbs`, etc.) need to be committed; there's no need to check whether a dist
file changed before committing.

## Commit workflow

Convention here is small commits made directly to `main` — not feature
branches. Skip creating a branch for routine changes; commit straight to
`main` unless asked to do otherwise.

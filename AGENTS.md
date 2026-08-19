# Project agent memory

This file is the project's committed home for project-intrinsic agent knowledge: build, test, release, architecture, and sharp-edge notes that should travel with the code.

- This is Hunter's GitHub profile README (renders on github.com/hmcdaniel03). The README prose is Hunter's final copy — do not reword it; visual/layout changes must keep his sentences byte-for-byte.
- Visual identity is deliberately minimal: one wordmark (`assets/wordmark-light.svg` / `-dark.svg`, swapped via `<picture>` + `prefers-color-scheme`). No badges, counters, stat cards, icon grids, GIFs, or emoji — those were removed on purpose (see PR #1).
- Accent colors come from Spunky's real brand palette, defined as CSS variables in `spunkytasks/Spunky` at `site/public/index.html` (light accent `#6D28D9`, dark accent `#B794F6`). Read that file for palette changes; don't guess hex values.
- README image assets must be self-contained SVGs (no external fonts/images — GitHub's proxy strips them); relative paths are rewritten by GitHub to `/raw/<ref>/…` URLs, so committed assets resolve on any branch.

## Maintaining this file

Keep this file for knowledge useful to almost every future agent session in this project.
Do not repeat what the codebase already shows; point to the authoritative file or command instead.
Prefer rewriting or pruning existing entries over appending new ones.
When updating this file, preserve this bar for all agents and keep entries concise.

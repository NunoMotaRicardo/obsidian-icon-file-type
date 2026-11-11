# Contributing

Bug reports and pull requests are welcome.

- **Bugs / features:** open an issue using the templates.
- **Pull requests:** branch off `main`, run `npm install`, `npm run build` and `npm run lint`, test in Obsidian, then open a PR.
- Do not commit `main.js`; it is built and attached to releases.

## Releasing

Releases are built and published by the Release workflow when a version tag is pushed.

1. Move the `[Unreleased]` entries in `CHANGELOG.md` under a new `## [x.y.z] - YYYY-MM-DD` heading.
2. `npm version <patch|minor|major>` bumps `package.json`, `manifest.json` and `versions.json`, commits, and tags `x.y.z` (no `v` prefix, set in `.npmrc`).
3. Push `main` first, then the tag: `git push origin main && git push origin x.y.z`.
4. The workflow lints, builds, verifies the tag, versions and assets, then publishes the release with `main.js`, `manifest.json` and `styles.css` and the changelog section as notes.

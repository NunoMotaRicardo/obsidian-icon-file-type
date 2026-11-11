# Contributing

Bug reports and pull requests are welcome.

- **Bugs / features:** open an issue using the templates.
- **Pull requests:** branch off `main`, run `npm install`, `npm run build` and `npm run lint`, test in Obsidian, then open a PR.
- Do not commit `main.js`; it is built and attached to releases.

## Releasing

1. Update `CHANGELOG.md`.
2. `npm version <patch|minor|major>` (bumps `package.json`, `manifest.json`, `versions.json`).
3. Push the commit, then push a tag that exactly matches the version, with no `v` prefix: `git tag 1.2.0 && git push origin 1.2.0`.
4. The Release workflow publishes `main.js`, `manifest.json` and `styles.css`.

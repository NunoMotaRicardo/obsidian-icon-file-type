# Icon File Type plugin

Obsidian plugin (TypeScript, esbuild). Entry `main.ts`; mappings of extension -> icon live in `FILE_ICONS`.

- `npm run dev` / `npm run build` / `npm run lint` (obsidianmd eslint rules must stay clean)
- Dev loop: build, copy `main.js manifest.json styles.css` into `<vault>/.obsidian/plugins/icon-file-type/`, then use the `obsidian-cli` skill (`obsidian plugin:reload id=icon-file-type`, `obsidian dev:errors`).
- Never change the plugin `id`. `main.js` is not committed.
- Release: `npm version <x.y.z>`, push the tag (no `v` prefix); the Release workflow publishes assets.

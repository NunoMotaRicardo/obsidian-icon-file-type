# Icon File Type

An [Obsidian](https://obsidian.md/) plugin that shows small file-type icons next to non-Markdown files in the **File Explorer** sidebar.

Office documents, PDFs, images, audio, video, archives, code files, and eBooks each get a recognisable icon so you can distinguish them at a glance without relying on the filename extension alone.

## Features

- Zero configuration — icons appear automatically on startup
- Stays in sync: icons update when you rename, create, or delete files
- Uses PNG icons for Office/PDF files and compact SVG badges for everything else
- Lightweight: no external dependencies, no network calls

## Supported file types

| Category      | Extensions                                       |
| ------------- | ------------------------------------------------ |
| Documents     | `.pdf`, `.doc`, `.docx`, `.odt`                  |
| Spreadsheets  | `.xls`, `.xlsx`, `.ods`                          |
| Presentations | `.ppt`, `.pptx`, `.odp`                          |
| Images        | `.png`, `.jpg`, `.jpeg`, `.gif`, `.webp`, `.svg`, `.bmp`, `.tiff` |
| Data          | `.csv`, `.json`, `.xml`, `.yaml`, `.yml`         |
| Archives      | `.zip`, `.rar`, `.7z`, `.tar`, `.gz`             |
| Audio         | `.mp3`, `.wav`, `.ogg`, `.flac`, `.m4a`, `.aac`  |
| Video         | `.mp4`, `.mov`, `.avi`, `.mkv`, `.webm`          |
| Web / Code    | `.html`, `.htm`, `.js`, `.ts`, `.py`, `.css`     |
| eBook         | `.epub`                                          |

## Installation

In Obsidian, open **Settings → Community plugins → Browse**, search for **Icon File Type**, then install and enable it.

### Manual install

Download `main.js`, `manifest.json` and `styles.css` from the [latest release](https://github.com/NunoMotaRicardo/obsidian-icon-file-type/releases/latest) into `<vault>/.obsidian/plugins/icon-file-type/`, then enable the plugin in **Settings → Community plugins**.

## Development

See [docs/setup.md](./docs/setup.md). In short: `npm install`, then `npm run dev` (watch) or `npm run build`.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

MIT, see [LICENSE](./LICENSE).

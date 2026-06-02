# MeltItDown

**Convert any file to Markdown — directly in your browser.**

> Industrial-grade file converter. No server. No uploads. No tracking.

---

## What it does

MeltItDown converts PDF, Word, Excel, CSV, HTML, images, and text files into clean Markdown — entirely in your browser. Files never leave your device.

For image conversion, it uses your own AI API key (Anthropic, OpenAI, or Google Gemini). You pay only for what you use.

## Supported formats

| Format | Engine | Requires API key |
|---|---|---|
| PDF | PDF.js (local) | No |
| DOCX / DOC | Mammoth.js (local) | No |
| XLSX / XLS / CSV | SheetJS (local) | No |
| HTML / TXT / MD | Built-in parser (local) | No |
| JPG / PNG / WEBP / GIF | Claude / GPT-4o / Gemini | Yes |

## Features

- Drag & drop or click to browse
- Multiple files → single combined Markdown output
- Download as `.md`, `.txt`, or `.html`
- Copy to clipboard
- AI provider selector (Anthropic, OpenAI, Google Gemini)
- Step-by-step guide to get your API key inside the app
- Session-only key storage — cleared on tab close

## Security

- Files processed in browser memory only — never uploaded
- API keys stored in `sessionStorage` (deleted on tab close)
- Optional `localStorage` persistence with explicit warning
- Keys cleared from DOM immediately after save
- Content Security Policy restricts outbound connections to AI provider APIs only
- No analytics, no tracking, no external dependencies beyond CDN libraries

## Live demo

🔗 [your-username.github.io/meltitdown](https://your-username.github.io/meltitdown)

## Deploy in 3 steps

See [DEPLOY.md](DEPLOY.md) for full instructions.

## License

MIT — free to use, modify, and distribute.

---

Built with PDF.js · Mammoth.js · SheetJS · Anthropic / OpenAI / Gemini APIs

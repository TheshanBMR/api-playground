# [API] Playground

> A no-login browser tool to test any public API — inspect headers, preview JSON/images/audio/PDF responses, and auto-generate code in 6 languages.

**[→ Live Demo](https://theshanbmr.github.io/api-playground)**

![API Playground Screenshot](https://i.imgur.com/placeholder.png)

---

## Features

- **No login, no install** — runs entirely in the browser as a single HTML file
- **All HTTP methods** — GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS
- **Request builder** — headers, query params, body (JSON/Form/Text/XML), auth (Bearer, Basic, API Key)
- **Smart response viewer** — auto-detects content type and renders accordingly:
  - `JSON` → syntax-highlighted with color-coded keys, strings, numbers
  - `Images` → inline preview with pixel dimensions
  - `Audio` → playable audio player
  - `Video` → inline video player
  - `PDF` → embedded PDF viewer
  - `HTML` → sandboxed iframe preview + source toggle
  - `Binary` → download button
- **Code generator** — auto-generates ready-to-run code for:
  - cURL · JavaScript Fetch · Axios · Python · Go · PHP
- **Request history** — last 50 requests, reload any with one click
- **Preset APIs** — JSONPlaceholder, Cat Fact, Joke API, IP lookup, Country Info, Open-Meteo Weather, and more

---

## Usage

No setup required. Just open `index.html` in any modern browser — or visit the live demo above.

```
1. Enter a URL
2. Set method, headers, params, body, or auth as needed
3. Click ▶ Send
4. Inspect the response or copy the generated code
```

---

## Local Development

```bash
git clone https://github.com/theshanbmr/api-playground.git
cd api-playground
open index.html   # or just double-click it
```

No build step. No dependencies. No Node.js required.

---

## CORS Note

Some APIs block browser requests due to CORS policy. When this happens, the **Code Gen** tab still generates working code you can run from a terminal or backend.

---

## Tech Stack

| What | How |
|------|-----|
| Framework | None — vanilla HTML/CSS/JS |
| Fonts | JetBrains Mono + Syne (Google Fonts) |
| Build tool | None |
| Dependencies | Zero |
| File count | 1 |

---

## License

MIT — do whatever you want with it.

# Aung Kaung Khant — Portfolio

Personal portfolio of **Aung Kaung Khant**, a full stack developer in Hpa-An, Myanmar,
strongest on the backend. Built as a single self-contained HTML file.

**Live:** https://www.aungkaungkhant.com/

---

## What's in it

Five production systems, each written up around the one problem that took the real thinking:

| System | What it is |
|---|---|
| **PhiLo POS** | Multi-branch inventory & point of sale, co-owned — offline-first, in production with paying customers |
| **Blingo** | E-commerce & consignment platform — backend lead |
| **MyTogether Shop** | Multi-vendor marketplace & delivery API — live on Google Play |
| **Raveon Live Mini** | Live event & artist tipping platform with its own payment integration |
| **DevPulse AI** | Bilingual (Burmese + English) RAG document & code Q&A |

## How it's built

No framework, no build step, no dependencies — one `index.html` you can open directly
in a browser or drop on any static host.

- Layout is a bento grid that reflows across three breakpoints
- Background is a tinted ground with a graph-paper grid, three slow-drifting colour
  fields and an SVG grain layer
- An intro splash on first load — monogram, name and a hairline that fills while the
  fonts settle; shown once per tab, skipped on any click or key, on deep links and
  when JavaScript is off
- Light by default with a dark toggle; the choice is remembered in `localStorage`
- Navigation is a scroll map — the ticks sit where the sections actually are in the
  document, and a marker tracks reading position
- The portrait is a cut-out embedded as a WebP data URI, so the page stays one file
- Fonts: Hanken Grotesk and IBM Plex Mono via Google Fonts

## Running it

```bash
# open directly
xdg-open index.html

# or serve it, to check it on a phone on the same network
python3 -m http.server 5173
```

## Contact

- **Email** — dev.aungkaungkhant@gmail.com
- **LinkedIn** — https://www.linkedin.com/in/aung-kaung-khant-bounce-7682ab245/
- **GitHub** — https://github.com/aungkaungkhant-nssh

Open to full stack roles — remote, or relocation with visa sponsorship — and freelance backend work.

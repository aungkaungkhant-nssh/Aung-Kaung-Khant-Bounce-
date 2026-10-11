# Aung Kaung Khant — Portfolio

Personal portfolio of **Aung Kaung Khant**, a full stack developer in Hpa-An, Myanmar,
strongest on the backend. Built as a single self-contained HTML file.

**Live:** https://www.aungkaungkhant.com/

---

## What's in it

The same content, in the same order, as the résumé PDF:

| Section | What it covers |
|---|---|
| **Experience** | Raveon Live Mini (Ravus Law Chamber Company), Blingo (YEC Company, backend lead) and MyTogether Shop (freelance, live on Google Play) |
| **Projects** | PhiLo POS (side product, in production with paying customers) and DevPulse AI (personal, bilingual RAG) |
| **Technical Skills** | Backend, Frontend, Data & Ops, AI & Testing |
| **Education & Languages** | B.C.Sc., AWS certification in progress, Burmese and English |

The page is written up as API documentation: each section is an endpoint
(`GET /me`, `GET /experience/yec`, `POST /contact`) with the prose on the left and the
same facts as a JSON response on the right.

## How it's built

No framework, no build step, no dependencies — one `index.html` you can open directly
in a browser or drop on any static host.

- Three columns: endpoint list, prose, and a dark request/response panel that stays in
  view while its section is read
- The endpoint list highlights the section being read; on phones it becomes a drawer
  and the response panel drops under the prose
- "Run" on a panel replays its response; "Copy email" on the contact endpoint
- Light by default with a dark toggle; the choice is remembered in `localStorage`
- The portrait is embedded as a WebP data URI, so the page stays one file
- Fonts: Inter and JetBrains Mono via Google Fonts

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

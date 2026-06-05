# Betopian Briefings

Executive slide decks for the **Betopian** mobile app (Betopia Group). Built for leadership and management reviews.

## Live site

| Page | URL |
|------|-----|
| **Briefings hub** | https://engrmehedihasanshuvo.github.io/betopian-briefings/ |
| **Mancom deck (Jun 2026)** | https://engrmehedihasanshuvo.github.io/betopian-briefings/versions/2026-06-06-mancom/index.html |

## Current versions

| Version | Title | Date | Slides |
|---------|-------|------|--------|
| `2026-06-06-mancom` | Management Committee Briefing | 6 June 2026 | 14 |

**Highlights:** Android v1.0.0 · 29 live modules · 74% platform complete · iOS TestFlight beta

## Presenting

Open a deck in the browser. Use:

- **→** or **Space** — next slide
- **←** — previous slide
- **O** — slide overview
- **N** — speaker notes (if enabled)

Works on desktop and mobile browsers. No install required.

## Folder structure

```
presentations/
├── index.html              # Version picker (hub)
├── README.md
└── versions/
    └── 2026-06-06-mancom/
        ├── index.html      # Slide deck
        └── assets/         # Screenshots, logos, QR
```

## Add a new briefing

1. Copy an existing version folder:
   ```
   versions/2026-06-06-mancom/  →  versions/YYYY-MM-DD-name/
   ```
2. Edit `index.html` and update screenshots in `assets/`.
3. Add a new card in the root `index.html` hub.
4. Commit and push:

   ```bash
   git add .
   git commit -m "Add briefing: YYYY-MM-DD name"
   git push
   ```

GitHub Pages redeploys automatically from `main`.

## Maintainer

**Mehedi Hasan Shuvo** · Software Engineer · Betopia Group

---

Betopia Group · Betopian mobile app · Internal & leadership briefings

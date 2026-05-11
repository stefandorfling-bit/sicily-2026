# Picture it… Sicily 2026 🌊

Stefan & Nimrod's trip planning page for Siracusa, Sicily — 31 July to 3 August 2026.

## Project structure

```
/
├── index.html        ← The entire site (single-page)
├── images/
│   ├── together.jpg  ← Hero photo (Stefan & Nimrod together)
│   ├── stefan.jpg    ← Stefan's portrait
│   └── nimrod.jpg    ← Nimrod's portrait
├── vercel.json       ← Vercel static site config
└── README.md
```

## Adding your photos

Save your three photos into the `images/` folder with these exact filenames:

| File | What it is |
|------|-----------|
| `images/together.jpg` | The photo of both of you (used as the hero image) |
| `images/stefan.jpg` | Stefan's solo portrait |
| `images/nimrod.jpg` | Nimrod's solo portrait |

The page uses `onerror` fallbacks, so it renders gracefully without the images too.

## Deploying to Vercel

### First time

1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import your repo.
3. Vercel auto-detects it as a static site. Hit **Deploy**. Done.

### Subsequent updates

```bash
git add .
git commit -m "Update itinerary / add flights / etc."
git push
```

Vercel redeploys automatically on every push to `main`.

## What still needs filling in

- [ ] **Flights** — add booking details in the Flights section (template comment in the HTML)
- [ ] **Itinerary** — fill in the day-by-day activities
- [ ] **Restaurants** — add your picks (template comment in the HTML)
- [ ] **Photos** — drop the three images into `images/`

---

*La vita è bella.* ✦

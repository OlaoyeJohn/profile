# Biwa Technology — Analytics & AI Portfolio

A fast, no-build portfolio to showcase Analytics & AI projects. Built with vanilla **HTML/CSS/JS** and hosted on **GitHub Pages**.

---

## 🚀 Quick Start

1. **Create repository**
   - Name: `yourusername.github.io` (or `biwatechnology.github.io`).
   - Add `index.html` (from this project) at the repo root.

2. **Enable GitHub Pages**
   - Repo → **Settings** → **Pages** → Build & deployment: **Deploy from a branch**.
   - Branch: `main` (root). Save.
   - Visit: `https://yourusername.github.io`.

3. **Branding**
   - Replace logo in the header `<img>` with `/assets/biwa-logo.png`.
   - Update `<title>` and `<meta name="description">`.
   - Optional: Add `CNAME` file with `www.biwatechnology.com` and set DNS to GitHub Pages.

---

## ✍️ Add / Edit Projects
Projects live in a simple JS array inside `index.html`:

```js
const PROJECTS = [
  {
    name: "Container Inspection Prediction",
    status: "Case Study",
    description: "RandomForest model to predict customs exam and palletization.",
    cover: "https://…",
    tags: ["ML","Ports","Python"],
    tech: ["Python","pandas","scikit-learn"],
    links: { demo: "#", code: "#", writeup: "#" }
  },
  // … add more
];
```

**Fields**
- `name` — project title
- `status` — Demo / Prototype / Case Study / Guide / Template
- `description` — one-liner value proposition
- `cover` — image URL (Unsplash or your own)
- `tags` — for filtering (e.g., `"Power BI"`, `"Kafka"`)
- `tech` — visible mini stack (e.g., Python • DAX)
- `links` — `demo`, `code`, `writeup`

---

## 🌗 Theme
- Theme switcher included (🌙/☀️). Preference is stored in `localStorage`.
- Default follows system (`prefers-color-scheme`).

---

## 🧩 Optional Enhancements
- **Blog**: Switch to Jekyll for posts and RSS. Keep the same index as a custom homepage.
- **Analytics**: Add Plausible or GA snippet in `<head>`.
- **SEO**: Add Open Graph & Twitter Card meta tags.
- **Images**: Move assets to `/assets/` folder and compress.
- **CI**: Use GitHub Actions to run a link checker on push.

---

## 📁 Suggested Structure
```
.
├── index.html
├── assets/
│   ├── biwa-logo.png
│   └── covers/*
├── CNAME              # optional
└── README.md
```

---

## 🔗 Useful Links
- GitHub Pages docs: https://docs.github.com/pages
- Unsplash (free images): https://unsplash.com/

---

## 📜 License
MIT — do whatever, just keep the copyright.


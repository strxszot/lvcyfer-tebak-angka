# lvcyfer — Tebak Angka (Web + Terminal)

**Developed by lvcyfer**

This repository contains two simple implementations of the classic *Guess the Number* game:
- **Web**: A single-file HTML + JavaScript game (`/web/index.html`) ready to upload to any static hosting (GitHub Pages, Netlify, Vercel).
- **Terminal**: A Python CLI version (`/terminal/tebak_angka.py`) that runs in any terminal with Python 3 installed.

---

## Demo (placeholder)
Live demo (replace after deploy): https://lvcyfer.github.io/

---

## Contents
```
lvcyfer/
├── web/
│   └── index.html
├── terminal/
│   └── tebak_angka.py
└── README.md
```

---

## How to run

### Web (static hosting)
1. Upload the files in `/web` (especially `index.html`) to your hosting provider.
2. For GitHub Pages:
   - Create a new repository named `lvcyfer` on GitHub.
   - Push the `/web` contents to the repo root (or the `gh-pages` branch).
   - Enable GitHub Pages in the repository settings. Your site will be available at `https://<username>.github.io/lvcyfer/`.
3. For Netlify/Vercel: deploy the `/web` folder as a static site.

### Terminal (local)
```bash
python3 terminal/tebak_angka.py
```

---

## Customization & Tips
- Edit `web/index.html` to change styles, texts, or game behavior.
- Edit `terminal/tebak_angka.py` to add score saving or difficulty levels.
- If you want I can create a GitHub Actions workflow to auto-deploy `/web` to GitHub Pages when you push to `main`.

---

## License
MIT License — feel free to reuse and adapt for personal projects.

---
© lvcyfer

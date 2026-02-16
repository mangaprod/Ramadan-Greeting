# Ramadan Greeting Card

A simple static greeting-card web page that lets users type their name and download a personalized Ramadan card.

## Files

- `index.html` – app UI and logic
- `Ramadan Greeting BG.jpeg` – card background used inside canvas
- `Manga BG.png` – page background
- `Manga logo.svg` – logo shown on portrait/mobile screens

## Local preview

Open `index.html` directly, or run a local server for best browser compatibility:

```bash
python3 -m http.server
```

Then open: `http://localhost:8000`

## Deploy to GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`.

1. Push this project to a GitHub repository.
2. In GitHub: **Settings → Pages → Source** set to **GitHub Actions**.
3. On each push to `main`, the site deploys automatically.

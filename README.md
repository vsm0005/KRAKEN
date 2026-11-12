# Kraken

**Beyond Reality. Beyond Limits.**

A concept website for Kraken, an affordable cooling pad for gaming laptops. Built with React and Vite.

> The Kraken cooling pad is a preliminary concept. Product specifications, pricing, market demand, and performance claims all require validation. Nothing on the site is for sale.

## What's on the site

- An interactive airflow illustration (fan speed and angle controls)
- The Kraken brand band, the problem, the five product features, and the Entry and Premium models
- A testing roadmap and a list of claims that are not yet earned
- Target audience, FAQ, and a button that opens a Google Form to collect opinions

## Run it locally

```bash
npm install
npm run dev
```

Open the address Vite prints (usually http://localhost:5173).

## Build

```bash
npm run build
npm run preview
```

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. In the repository, open **Settings > Pages** and set **Source** to **GitHub Actions**.
3. Push to `main`. The workflow in `.github/workflows/deploy.yml` builds and publishes the site.

## Feedback form

The "Share your opinion" button in the `Join` component (`src/App.jsx`) opens a Google Form. To use a different form, change the `FORM_LINK` value there.

## Project structure

```
src/App.jsx          Page sections and content
src/styles.css       All styles
src/main.jsx         React entry point
public/              Logo (kraken-logo.png) and favicon
```

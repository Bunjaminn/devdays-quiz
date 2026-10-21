# devdays-quiz

A colorful, single-file space-themed quiz built with plain HTML, CSS, and JavaScript. The app is fully dependency-free and runs directly in the browser.

## Features

- Single-file app (`index.html`)
- No runtime dependencies
- Animated space-themed UI
- Countdown timer for each question
- Score tracking and final mission summary
- Responsive layout for desktop and mobile

## Run locally

1. Clone the repository.
2. Open `index.html` in a browser, or serve it locally with a simple static server.

Example using Python:

```bash
cd devdays-quiz
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

This repository includes a GitHub Actions workflow for GitHub Pages deployment. To make the site live:

1. In GitHub, open the repository.
2. Go to Settings → Pages.
3. Set the source to GitHub Actions.
4. Merge this branch into the default branch (`main`).
5. GitHub Actions will build and deploy the site automatically.

Expected live URL format:

```text
https://Bunjaminn.github.io/devdays-quiz
```

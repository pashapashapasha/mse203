# MS&E 203 — Course Syllabus Site

Single-page website for **Stanford MS&E 203: Building and Evaluating AI Products and Agents** (Fall 2026).

- **Live site:** https://pashapashapasha.github.io/mse203/
- **Source:** `index.html` (self-contained — HTML + inline CSS, no build step)

## How it deploys

Every push to `main` runs the GitHub Actions workflow in `.github/workflows/deploy-pages.yml`, which mirrors `index.html` to the `gh-pages` branch. GitHub Pages serves that branch.

## Editing

Edit `index.html` directly. To propose changes for review, open a pull request against `main`.

## Instructors

- Madeleine Udell — Professor, MS&E, Stanford
- Darius Emrani — CEO, Scorecard AI
- Pasha Nahass — Product Lead, Google DeepMind (Gemini App)

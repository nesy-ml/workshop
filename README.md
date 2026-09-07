# NeSyML workshop website

This repository contains the public website for NeSyML workshops.

- Current workshop: [NeSyML 2026 at ACML](https://nesy-ml.github.io/workshop/acml-2026/)
- Conference: [ACML 2026](https://www.acml-conf.org/2026/)

## Structure

The site is plain HTML, CSS, and JavaScript. Each workshop has its own directory; the repository root redirects to the current workshop.

```text
acml-2026/
  index.html
  styles.css
  script.js
  assets/
```

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/acml-2026/`.

## Publishing

GitHub Pages serves the `main` branch from the repository root. Changes pushed to `main` are published automatically.

Workshop details should be updated only after confirmation from the organizing committee. Image sources are listed in [CREDITS.md](./CREDITS.md).

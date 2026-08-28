# TacForcing project page

Project website for **TacForcing: Streaming Action Generation with Execution-Time Tactile Feedback**.

The page is built with [Astro](https://astro.build/) using Roman Hauksson-Neill's [academic project page template](https://github.com/RomanHauksson/academic-project-astro-template). Paper figures are converted from PDF at build time, and the real-world demonstrations are pre-encoded as browser-compatible H.264/MP4 videos at 5× speed.

## Local development

Node.js 24 or newer is recommended.

```bash
npm install
npm run dev
```

Open `http://localhost:4321` to preview the page.

## Production build

```bash
npm run build
```

The static output is written to `dist/`.

## Deploy to GitHub Pages

The included `.github/workflows/astro.yml` workflow builds and deploys the page on pushes to `main`. In the GitHub repository settings, set **Pages → Source** to **GitHub Actions**.

## Main content

- `src/paper.mdx` — page copy, authors, figures, results, and demo layout
- `src/assets/videos/` — optimized 5× real-world demonstrations
- `public/paper.pdf` — downloadable paper

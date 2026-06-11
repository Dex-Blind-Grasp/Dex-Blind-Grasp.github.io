# Blind Dexterous Grasping Project Page

This repository contains the GitHub Pages website for **Blind Dexterous Grasping via Real2Sim2Real Tactile Policy Learning**.

The site is built with Astro and MDX. Page content lives in `src/paper.mdx`, with reusable layout and media components under `src/components/`.

## Local Development

```bash
npm install
npm run dev
```

Open `http://localhost:4321` to preview the page locally.

## Build

```bash
npm run build
```

The static site is generated in `dist/`.

## Deploy

Pushing to `main` triggers `.github/workflows/astro.yml`, which builds and deploys the page to GitHub Pages.

## Project Structure

- `src/paper.mdx` - main page content and metadata
- `src/assets/` - figures, videos, and experiment media
- `src/components/` - page sections and media helpers
- `src/styles/global.css` - global theme and responsive layout styles
- `public/` - static public assets such as favicon and social thumbnail

## Credits

The site was adapted from Roman Hauksson's Astro academic project page template, originally inspired by the Nerfies project page.

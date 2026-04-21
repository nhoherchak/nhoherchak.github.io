# nhoherchak.github.io

Personal portfolio website built with [Eleventy](https://www.11ty.dev/) and [Tailwind CSS](https://tailwindcss.com/).

## Prerequisites

- [Node.js](https://nodejs.org/) v20+
- [nvm](https://github.com/nvm-sh/nvm) (recommended for managing Node versions)

## Setup

```bash
nvm use 20
npm install
```

## Development

Start the dev server with live reload and CSS watching:

```bash
npm run dev
```

This runs Tailwind CSS and Eleventy in parallel. The site will be available at `http://localhost:8080`.

## Production Build

```bash
npm run build
```

Output goes to `_site/`.

## Project Structure

```
src/
  _includes/layouts/base.njk  - Shared page layout (nav + footer)
  _data/site.json              - Site-wide data
  css/input.css                - Tailwind CSS entry point
  css/custom.css               - Custom styles
  images/                      - Images and PDFs
  *.njk                        - Page templates
```

## Deployment

Deploys automatically to GitHub Pages via GitHub Actions on push to `master`.

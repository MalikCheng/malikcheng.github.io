# Malik Cheng - Personal Website

A modern personal website built with **Astro** + **TailwindCSS**.

## Tech Stack

- [Astro](https://astro.build) - Static site generator
- [TailwindCSS](https://tailwindcss.com) - Utility-first CSS framework
- TypeScript

## Quick Start

```bash
# Install dependencies
npm install

# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to GitHub Pages

1. Create repository named `malikcheng.github.io`

2. Push to GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/MalikCheng/malikcheng.github.io.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to Repository → Settings → Pages
   - Source: Deploy from `main` branch
   - Folder: `/ (root)`

4. Visit: https://malikcheng.github.io

## Customization

Edit `src/pages/index.astro` to update:
- Skills array
- Projects list
- Contact information
- About section

## Project Structure

```
personal-website/
├── src/
│   ├── pages/
│   │   └── index.astro     # Main page
│   └── layouts/
│       └── Layout.astro    # Base layout
├── public/
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

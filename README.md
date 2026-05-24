# Wisdom Benson Personal Website

Personal academic portfolio for GitHub Pages, built with Vite, React, TypeScript, Tailwind CSS v4, and shadcn/ui components.

## Local Development

```powershell
pnpm install
pnpm dev
```

## Validation

```powershell
pnpm exec tsc -b --pretty false
pnpm exec vite build
pnpm exec eslint src --max-warnings=0
```

## Deployment

This repository is configured for GitHub Pages through `.github/workflows/pages.yml`. Push `main` to `Wisemanking001/Wisemanking001.github.io`, then set GitHub Pages to deploy from GitHub Actions if the repository settings do not already do so.

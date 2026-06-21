# Vegetable Planting Calendar GitHub Pages External Link Page

This directory contains the static GitHub Pages overview page for Vegetable Planting Calendar.

Live product site:

https://www.vegetableplantingcalendar.com

GitHub Pages URL:

https://szy130github.github.io/vegetable-planting-calendar-pages/

## Purpose

The production site is a Next.js application hosted separately from GitHub Pages. This directory only publishes a static overview page with product context, real screenshots, recent updates, FAQ, and links to the live site.

## Local Verification

From the main project root:

```bash
npm test -- tests/github-pages-static.test.ts
```

## Publishing

The `github-pages/` directory is intended to be pushed as an independent public GitHub Pages repository:

```bash
gh repo create szy130GitHub/vegetable-planting-calendar-pages --public --source . --remote origin --push --description "Vegetable Planting Calendar GitHub Pages external link page" --homepage https://www.vegetableplantingcalendar.com
```

Then enable GitHub Pages from the repository root on the `main` branch.

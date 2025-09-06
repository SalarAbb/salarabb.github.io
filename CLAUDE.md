# CLAUDE.md

# Project: Personal Website - Salar Abbaspourazad

## Overview
This is a personal portfolio website built with Astro.js for Salar Abbaspourazad, a Machine Learning Scientist at Apple. The site features a retro/pixelated aesthetic with interactive elements and multiple scene backgrounds.

## Tech Stack
- **Framework**: Astro 5.13.5
- **Build Target**: Static site generation
- **Deployment**: GitHub Pages (salarabb.github.io)
- **Styling**: CSS-in-JS with retro/pixel art styling
- **Fonts**: Press Start 2P, VT323 (Google Fonts)

## Key Features
- Interactive retro-style interface with scene switching
- Responsive design with mobile optimizations
- Dropdown "About Me" section
- Navigation arrows and keyboard shortcuts
- Auto-rotating background scenes
- Animated equalizer bars
- Social icons and CV/Blog access buttons

## Project Structure
```
/
├── public/
│   └── CV.pdf                    # Resume/CV file
├── src/
│   ├── components/
│   │   └── LofiPlayer.astro     # Audio player component
│   ├── layouts/
│   │   └── BaseLayout.astro     # Base layout template
│   └── pages/
│       ├── index.astro          # Main landing page
│       ├── desk.astro           # Desk scene page
│       ├── office.astro         # Office scene page
│       ├── presentations.astro  # Presentations page
│       ├── study.astro          # Study scene page
│       └── workshop.astro       # Workshop scene page
├── astro.config.mjs             # Astro configuration
├── package.json                 # Dependencies and scripts
└── tsconfig.json                # TypeScript configuration
```

## Scripts
- `npm run dev` - Start development server at localhost:4321
- `npm run build` - Build production site to ./dist/
- `npm run preview` - Preview build locally
- `npm run astro` - Run Astro CLI commands

## Site Content
The main page features information about Salar Abbaspourazad:
- Machine Learning Scientist at Apple
- PhD in Computer Science from USC (supervised by Prof. Maryam Shanechi)
- BSc from Sharif University of Technology in Electrical Engineering
- Research focus: representation learning, self-supervised learning, time-series data
- Background in brain-machine interfaces, latent variable models, neural networks

## Design Notes
- Retro/pixel art aesthetic with pixelated overlays
- Dark theme with gradient backgrounds
- Interactive elements with hover effects
- Keyboard shortcuts (Arrow keys for scene navigation, C for CV, B for blog)
- Auto-rotation between scenes every 12 seconds
- Animated equalizer visualization

## Development Notes
- Uses modern Astro features with static site generation
- Inline styles for component-specific styling
- JavaScript for interactivity (scene switching, dropdown, animations)
- Responsive design with mobile breakpoints
- Font loading from Google Fonts

## Deployment
- Configured for GitHub Pages deployment
- Static output targeting salarabb.github.io
- All assets bundled for production build
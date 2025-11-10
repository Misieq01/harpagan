# Harpagan

A simple multi-page website built with Astro.js, hosted on GitHub Pages.

## Features

- 🚀 Built with Astro.js
- 📱 Responsive design (desktop and mobile support)
- 🎨 Three pages with routing: Home, About, and Contact
- 🔄 Automatic deployment to GitHub Pages via GitHub Actions

## Development

### Prerequisites

- Node.js 20 or higher
- npm

### Installation

```bash
npm install
```

### Local Development

Start the development server:

```bash
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

### Build

Build the site for production:

```bash
npm run build
```

### Preview

Preview the production build locally:

```bash
npm run preview
```

## Project Structure

```
/
├── public/          # Static assets (favicon, images, etc.)
├── src/
│   ├── layouts/     # Layout components
│   │   └── Layout.astro
│   └── pages/       # Page components (routes)
│       ├── index.astro    # Home page (/)
│       ├── about.astro    # About page (/about)
│       └── contact.astro  # Contact page (/contact)
├── astro.config.mjs # Astro configuration
└── package.json
```

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### GitHub Pages Setup

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Build and deployment", set:
   - Source: GitHub Actions
4. The workflow will automatically deploy your site

The site will be available at: `https://Misieq01.github.io/harpagan/`

## License

ISC
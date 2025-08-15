# Pharmique Coming Soon Page

A simple coming soon page for Pharmique, built with Astro and deployed on Cloudflare Workers.

## What This Is

This is a minimal coming soon page that displays a single image (`ComingSoon1.jfif`) centered on the page with a dark background.

## Features

- ✅ Simple, clean design
- ✅ Responsive image display
- ✅ Dark theme
- ✅ Deployed on Cloudflare Workers
- ✅ Fast loading and performance

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:4321`

### Building

To build for production:
```bash
npm run build
```

### Deployment

To deploy to Cloudflare Workers:
```bash
npm run deploy
```

## Project Structure

```
pharmique-soon-page/
├── src/
│   ├── components/
│   │   └── BaseHead.astro
│   ├── pages/
│   │   └── index.astro
│   ├── styles/
│   │   └── global.css
│   └── consts.ts
├── public/
│   └── images/
│       └── ComingSoon1.jfif
└── astro.config.mjs
```

## Customization

To change the coming soon image:
1. Replace `public/images/ComingSoon1.jfif` with your new image
2. Update the image path in `src/pages/index.astro` if needed

## Technologies Used

- [Astro](https://astro.build/) - Static site generator
- [Cloudflare Workers](https://workers.cloudflare.com/) - Deployment platform
- TypeScript - Type safety

## License

This project is private and proprietary to Pharmique.

# Liz's Cleaning Service Website

A modern, fast, and SEO-optimized static website for Liz's Cleaning Service in Cherokee County, GA.

## 🚀 Built With

- **Astro** - Modern static site generator
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Type-safe JavaScript

## 🌟 Features

- ✅ Fully responsive design (mobile & desktop)
- ✅ SEO optimized with meta tags and structured data
- ✅ Fast load times (static HTML generation)
- ✅ Clean, modern design
- ✅ Dark mode support
- ✅ Service showcase
- ✅ Transparent pricing
- ✅ Photo gallery
- ✅ Customer testimonials

## 📋 Services Offered

- **Residential Cleaning** - Deep cleaning for homes
- **Commercial Cleaning** - Professional workspace cleaning
- **Airbnb Turnover** - Fast, same-day turnover service

## 💰 Pricing

- 1 Bedroom: $80
- 2 Bedrooms: $110
- 3 Bedrooms: $140

## 🛠️ Development

### Prerequisites

- Node.js (v18 or higher)
- npm

### Installation

```bash
npm install
```

### Development Server

```bash
npm run dev
```

Visit `http://localhost:4321` to view the site.

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
/
├── public/              # Static assets (images, favicon, etc.)
├── src/
│   ├── components/      # Reusable Astro components
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── Pricing.astro
│   │   ├── Gallery.astro
│   │   ├── Testimonials.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/         # Page layouts
│   │   └── Layout.astro
│   ├── pages/           # Page routes
│   │   └── index.astro
│   └── styles/          # Global styles
│       └── global.css
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind configuration
└── package.json
```

## 🚀 Deployment

### GitHub Pages

1. Build the site:

   ```bash
   npm run build
   ```

2. Update `astro.config.mjs` to set your base path (if deploying to a subdirectory):

   ```js
   export default defineConfig({
     site: 'https://yourusername.github.io',
     base: '/your-repo-name'
   });
   ```

3. Deploy the `dist` folder to GitHub Pages using GitHub Actions or manually push to the `gh-pages` branch.

## 📝 Customization

### Update Contact Information

Edit `src/components/Footer.astro` and `src/components/Contact.astro` to update:

- Phone number
- Email address
- Social media links

### Update Business Hours

Edit `src/components/Footer.astro` to modify business hours.

### Add Real Photos

Replace placeholder gallery items in `src/components/Gallery.astro` with actual cleaning photos. Store images in the `public/` directory.

## 📊 SEO Features

- ✅ Semantic HTML structure
- ✅ Meta tags (title, description, keywords)
- ✅ Open Graph tags for social sharing
- ✅ Structured data (LocalBusiness schema)
- ✅ Mobile-friendly design
- ✅ Fast loading times
- ✅ Clean URLs

## 📄 License

Copyright © 2025 Liz's Cleaning Service. All rights reserved.

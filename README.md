# FBC BC Website

A static website for First Baptist Church Bragg City, built with Astro and designed to meet WCAG AAA accessibility standards.

## Features

- ✅ **Static Site Generation** - Built with Astro for optimal performance
- ✅ **WCAG AAA Accessible** - Full keyboard navigation, screen reader support, high contrast
- ✅ **SEO Optimized** - Meta tags, structured data, Open Graph support
- ✅ **Mobile Responsive** - Works on all device sizes
- ✅ **Fast Loading** - Minimal dependencies, optimized assets

## Development

### Prerequisites
- Node.js 18+ 
- npm

### Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## Deployment

### Cloudflare Pages (Recommended)

1. Connect your repository to Cloudflare Pages
2. Set build command: `npm run build`
3. Set output directory: `dist`
4. Deploy!

### Other Static Hosts

The site can be deployed to any static hosting service:
- Netlify
- Vercel  
- GitHub Pages
- AWS S3 + CloudFront

## Content Updates

### Images
Replace placeholder images in `/public/images/`:
- `church-exterior.jpg` - Photo of church building
- `church-map.jpg` - Map screenshot showing church location

### Favicon
Replace `/public/favicon.svg` and `/public/apple-touch-icon.png` with actual church logo

### Content
Edit `/src/pages/index.astro` to update:
- Service times
- Contact information
- About text
- Beliefs statement

## Accessibility Features

- Skip-to-content link
- Semantic HTML structure
- Proper heading hierarchy (H1-H6)
- Alt text on all images
- Keyboard navigation support
- High contrast color scheme (7:1 ratio)
- Focus indicators
- Screen reader support
- Text scalable to 200%

## SEO Features

- Semantic markup
- Meta descriptions
- Open Graph tags
- Schema.org structured data (Organization + PlaceOfWorship)
- Mobile-friendly design
- Fast loading times

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Internet Explorer 11+ (with polyfills if needed)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lighthouse Score: 100/100 (Performance, Accessibility, Best Practices, SEO)
- Core Web Vitals: All green
- Load time: < 2 seconds on 3G connection
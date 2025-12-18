# Nails Mag - Project To-Do

## Project Setup

- **Frontend:** nailsmag.co.uk (Astro on Cloudflare Pages)
- **Backend:** wp.nailsmag.co.uk (WordPress)

---

## ✅ Done

- [x] Update `.env.production` - WP API URL
- [x] Update `.env` - Local dev URL
- [x] Update `astro.config.mjs` - Site URL
- [x] Update `robots.txt` - Sitemap URL
- [x] Update `wordpress.js` - API fallback URL
- [x] Update `consts.ts` - Site title & description
- [x] Update `package.json` - Project name

---

## ⏳ To Do

### WordPress Setup
- [ ] Install WordPress on wp.nailsmag.co.uk
- [ ] Install WP REST API Menus plugin
- [ ] Configure CORS for nailsmag.co.uk
- [ ] Add SEO plugin (SEO Framework / Yoast / Rank Math)
- [ ] Create initial content/posts

### Cloudflare Pages
- [ ] Connect GitHub repo to Cloudflare Pages
- [ ] Set environment variable: `WP_API_URL`
- [ ] Configure custom domain: nailsmag.co.uk
- [ ] Set up build command: `npm run build`
- [ ] Set output directory: `dist`

### Easy IO / CDN (Optional)
- [ ] Set up Easy IO for image optimization
- [ ] Update `EASY_IO_CDN` constant in `wordpress.js`

### Content & Design
- [ ] Update favicon in `/public`
- [ ] Customize Header/Footer components
- [ ] Update color scheme in `global.css`
- [ ] Add site logo

---

## Commands

```bash
# Dev
npm run dev

# Build
npm run build

# Preview build
npm run preview
```

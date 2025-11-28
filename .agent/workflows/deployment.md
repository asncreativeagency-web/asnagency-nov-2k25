---
description: How to deploy the ASN Technologies website
---

# Deployment Checklist for ASN Technologies Website

## Pre-Deployment Tasks

### 1. Content Review
- [x] Remove unused portfolio items (Air Pro by Molekule, Tony's Chocolonely)
- [x] Update project images to use .png format
- [x] Update project 4 to "Morvian Store"
- [x] Simplify navigation menus
- [x] Connect contact form to Formspree
- [x] Connect newsletter forms to Formspree

### 2. SEO & Meta Tags
- [ ] Update page titles in all HTML files
- [ ] Add meta descriptions
- [ ] Add Open Graph tags for social sharing
- [ ] Add favicon
- [ ] Create robots.txt
- [ ] Create sitemap.xml

### 3. Performance Optimization
- [ ] Minify CSS files
- [ ] Minify JavaScript files
- [ ] Optimize images (compress)
- [ ] Add lazy loading for images
- [ ] Enable browser caching

### 4. Testing
- [ ] Test all navigation links
- [ ] Test contact form submission
- [ ] Test newsletter form submission
- [ ] Test on different browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices
- [ ] Check for broken images
- [ ] Validate HTML
- [ ] Check console for JavaScript errors

### 5. Analytics & Tracking
- [ ] Add Google Analytics
- [ ] Add Google Search Console
- [ ] Add Facebook Pixel (optional)

### 6. Security
- [ ] Add HTTPS (SSL certificate)
- [ ] Update all http:// links to https://
- [ ] Add security headers

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push all files to the repository
3. Enable GitHub Pages in repository settings
4. Custom domain setup (optional)

### Option 2: Netlify (Free, Recommended)
// turbo
1. Create account at netlify.com
2. Drag and drop the ashley folder
3. Site will be live instantly
4. Connect custom domain (optional)

### Option 3: Vercel (Free)
1. Create account at vercel.com
2. Import from GitHub or upload folder
3. Deploy with one click

### Option 4: Traditional Hosting (cPanel/FTP)
1. Purchase hosting (Hostinger, Bluehost, etc.)
2. Upload files via FTP/File Manager
3. Point domain to hosting

## Post-Deployment Tasks

1. **Submit to Search Engines**
   - Submit sitemap to Google Search Console
   - Submit to Bing Webmaster Tools

2. **Monitor Performance**
   - Use Google PageSpeed Insights
   - Check GTmetrix scores
   - Monitor uptime

3. **Regular Updates**
   - Update portfolio with new projects
   - Keep blog/newsletter content fresh
   - Monitor form submissions

## Quick Deploy Commands (for Netlify CLI)

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy
netlify deploy --prod
```

## Files to Exclude from Deployment

- .ps1 files (PowerShell scripts)
- .md files in .agent folder
- Any backup files
- Development notes

## Important URLs After Deployment

- Website: [Your domain]
- Formspree Dashboard: https://formspree.io/forms
- Analytics: https://analytics.google.com
- Search Console: https://search.google.com/search-console

# HSDS Website Deployment Notes

## Current Status
- New site built: `hsds-storybrand/` folder
- Static HTML/CSS/JS — ready to deploy anywhere
- Schema markup and SEO meta tags added

## When Ready to Deploy (GitHub Pages)

1. **Create a new repo** (or use existing) for the site
2. Push the `hsds-storybrand` contents to the repo root
3. Go to Settings → Pages → set source to `main` branch
4. Add custom domain: `humanscaledigitalsolutions.com`

### DNS Changes Needed
Point your domain to GitHub Pages:
- **A records** (for apex domain):
  ```
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
  ```
- **CNAME** (for www): `yourusername.github.io`

### Before Switching
- [ ] Check where domain is registered (Squarespace? Elsewhere?)
- [ ] Note any Squarespace features in use (forms, scheduling, etc.)
- [ ] Set up contact form alternative if needed (Formspree, Netlify Forms, etc.)
- [ ] Test site thoroughly
- [ ] Cancel Squarespace after DNS propagates (~24-48hrs)

## Alternative Hosts (if needed)
- **Netlify** — drag & drop, free forms
- **Vercel** — great for static sites
- **Cloudflare Pages** — fast global CDN

## Site Details (for schema)
- Business: Human Scale Digital Solutions
- Founded: 2012
- Service area: Northampton, Easthampton, Amherst, Hadley, Pioneer Valley
- Hours: Mon-Fri 9am-5pm
- Rate: $100/hour
- Phone: (413) 247-4090
- Email: ramzi@humanscaledigitalsolutions.com
- Services: Website Management, Marketing Support

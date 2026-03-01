# AZ Vape Vending — Deployment Guide

## Files Ready
- `index.html` — Main landing page
- `thank-you.html` — Form submission confirmation
- `robots.txt` — SEO basics

## Quick Deploy Options

### Option 1: Vercel (Recommended - Free)
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Drag & drop the `website` folder
4. Set custom domain: `azvapevending.com`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag & drop the `website` folder
3. Set custom domain

### Option 3: GitHub Pages (Free)
1. Create repo `azvapevending`
2. Push these files
3. Enable Pages in settings
4. Set custom domain

## Domain Setup

**Need to purchase:** `azvapevending.com`

Registrars:
- Namecheap (~$12/year)
- Cloudflare (~$10/year)
- Google Domains

After purchase, point DNS to your host:
- Vercel: Add CNAME to `cname.vercel-dns.com`
- Netlify: Add CNAME to `[yoursite].netlify.app`

## Form Setup (FormSubmit)

The contact form uses [FormSubmit.co](https://formsubmit.co) (free).

**First submission:**
1. Someone submits the form
2. FormSubmit sends verification email to `jack@rinngroup.com`
3. Click the verification link
4. All future submissions go straight to email

**To change email:** Edit the form action in `index.html`:
```html
<form action="https://formsubmit.co/YOUR_EMAIL" method="POST">
```

## After Deploy Checklist

- [ ] Purchase domain
- [ ] Deploy files
- [ ] Point DNS
- [ ] Test form (verify email)
- [ ] Set up Google Search Console
- [ ] Create Google Business Profile
- [ ] Add real machine photos when available

## Future Enhancements

- [ ] Add machine photos (Slim Tower 2.0)
- [ ] Add Kokomo's testimonial after install
- [ ] Blog for SEO content
- [ ] Google Analytics or Plausible

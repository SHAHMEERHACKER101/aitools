# AI Tools Directory - Deployment Guide

## 📦 What's Included

This folder contains your complete AI Tools Directory website with integrated ad scripts:

### HTML Pages (with ads)
- ✅ `index.html` - Main homepage with AI tools directory
- ✅ `about.html` - About page
- ✅ `contact.html` - Contact page
- ✅ `privacy.html` - Privacy policy

### Assets & Scripts
- ✅ `styles.css` - All CSS styles
- ✅ `script.js` - JavaScript functionality
- ✅ `ads-style.css` - Ad-related styles
- ✅ `favicon.svg` - Website icon

### SEO Files
- ✅ `sitemap.xml` - SEO sitemap
- ✅ `robots.txt` - Search engine directives
- ✅ `README.md` - Project documentation

### Configuration
- ✅ `.gitignore` - Git ignore rules

---

## 🎯 Ad Integration Complete

### Monetag Vignette Script
**Zone ID:** 10044037  
**Location:** Right after `<head>` tag on all pages  
**Type:** Non-intrusive vignette overlay

### Adsterra Banner
**Key:** 887446e87d539dda95fb5f54b8f5368a  
**Size:** 160x300  
**Location:** Before footer on all pages  
**Format:** iframe banner

---

## 🚀 Push to GitHub

### Step 1: Initialize Git Repository
```bash
cd "ai tools with ads"
git init
```

### Step 2: Add All Files
```bash
git add .
```

### Step 3: Commit Changes
```bash
git commit -m "Initial commit: AI Tools Directory with Monetag and Adsterra ads"
```

### Step 4: Add Remote Repository
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

### Step 5: Push to GitHub
```bash
git branch -M main
git push -u origin main
```

---

## 🌐 Deploy to Cloudflare Pages

### Option 1: GitHub → Cloudflare (Recommended)

1. Push code to GitHub (see above)
2. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. Go to **Workers & Pages** → **Create Application** → **Pages**
4. Select **Connect to Git**
5. Choose your GitHub repository
6. Configure:
   - Build command: *Leave empty*
   - Build output directory: `/`
   - Root directory: `/`
7. Click **Save and Deploy**

### Option 2: Direct Upload to Cloudflare

1. Create a ZIP file of ALL files in this folder
2. Go to Cloudflare Dashboard → **Workers & Pages** → **Pages**
3. Select **Upload assets**
4. Upload your ZIP file
5. Deploy!

---

## ⚙️ Post-Deployment Steps

### Required: Update Domain URLs
Replace `https://yourdomain.com` with your actual domain in:
- `index.html` (meta tags, canonical, Schema.org)
- `about.html` (meta tags)
- `contact.html` (meta tags)
- `privacy.html` (meta tags)
- `sitemap.xml` (all URLs)

### Optional: Update Email
Replace `info@yourdomain.com` with your actual email in:
- `contact.html`
- `privacy.html`

---

## ✅ Verification Checklist

After deployment:
- [ ] Test all pages load correctly
- [ ] Verify Monetag vignette ad appears
- [ ] Verify Adsterra banner displays
- [ ] Test search functionality
- [ ] Test category filtering
- [ ] Check mobile responsiveness
- [ ] Submit sitemap to Google Search Console
- [ ] Test all affiliate links

---

## 📊 Ad Performance

- **Monetag**: Vignette ads show on page navigation
- **Adsterra**: Banner visible before footer on all pages
- Both scripts load asynchronously to maintain page speed

---

## 🔗 Important Links

- [Monetag Dashboard](https://monetag.com/)
- [Adsterra Dashboard](https://www.adsterra.com/)
- [Google Search Console](https://search.google.com/search-console)
- [Cloudflare Pages](https://pages.cloudflare.com/)

---

**Ready to deploy! 🚀**

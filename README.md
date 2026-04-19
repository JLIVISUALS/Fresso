# Fresso Café — Website

A warm, rustic, professional multi-page website for Fresso Café.

---

## Files

```
fresso-cafe/
├── index.html      ← Home page
├── menu.html       ← Menu page
├── style.css       ← All styles
├── script.js       ← Interactivity
└── README.md       ← This file
```

---

## Customizing Before Launch

### 1. Update Contact Info
In both `index.html` and `menu.html`, find and replace:
- `123 Main Street / Your City, TX 00000` → your real address
- `(000) 000-0000` → your phone number
- `hello@frescocafe.com` → your email

### 2. Add Your Logo
Replace the text logo placeholder. In both HTML files, find `.logo-placeholder` and replace it with:
```html
<img src="logo.png" alt="Fresso Café" class="logo-img" style="height:50px;" />
```
Place your `logo.png` file in the same folder.

### 3. Add Hiring Link
In `index.html`, find this line:
```html
<a href="YOUR_HIRING_LINK_HERE" target="_blank" ...>
```
Replace `YOUR_HIRING_LINK_HERE` with your actual link (Indeed, LinkedIn, Google Forms, etc.)

### 4. Add Social Media Links
In both HTML files (footer section), replace:
- `YOUR_INSTAGRAM_LINK`
- `YOUR_FACEBOOK_LINK`
- `YOUR_TIKTOK_LINK`
- `YOUR_YELP_LINK`

### 5. Update Hours & Menu Prices
Edit directly in `index.html` and `menu.html`.

### 6. Add Real Photos
Replace `.about-img-placeholder` in `index.html` with:
```html
<img src="cafe-photo.jpg" alt="Inside Fresso Café" style="width:100%;height:100%;object-fit:cover;border-radius:2px;" />
```

---

## Connecting to a Domain

### Option A — Netlify (Free, Easiest)
1. Go to [netlify.com](https://netlify.com) and sign up
2. Drag your `fresso-cafe` folder into the Netlify dashboard
3. Your site goes live instantly at a `.netlify.app` URL
4. Go to **Domain Management** → Add your custom domain (e.g. `frescocafe.com`)
5. Follow Netlify's DNS instructions to point your domain

### Option B — GitHub Pages (Free)
1. Create a free GitHub account
2. Create a new repo named `frescocafe-website`
3. Upload all files to the repo
4. Go to Settings → Pages → Deploy from branch `main`
5. Add your custom domain under Pages settings

### Option C — Traditional Web Host (Hostinger, GoDaddy, Bluehost)
1. Purchase hosting + domain from provider
2. Open their File Manager or use FTP (FileZilla)
3. Upload all files to the `public_html` folder
4. Your domain will serve your site automatically

---

## Domain Purchase
Buy your domain at: [Namecheap](https://namecheap.com), [GoDaddy](https://godaddy.com), or [Google Domains](https://domains.google)

Recommended domain: `frescocafe.com` or `fressocafe.com`

---

*Built for Fresso Café ☕*

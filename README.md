# Telangana Vantillu — Eturnagaram Branch

Official website for the **Telangana Vantillu** restaurant, Eturnagaram branch
(Y Junction, Akulavari Ghanpur, Eturnagaram, Telangana 506165).

Built as a single static page — no build tools, no dependencies, no hosting cost.

- Main branch Instagram: <https://www.instagram.com/telangana.vantillu/>
- Eturnagaram branch Instagram: <https://www.instagram.com/telanganavantilluenr/>
- **Now open** — tiffins from morning, soups & mains from 11:30 AM

---

## What's inside

```
telangana-vantillu-eturnagaram/
├── index.html          ← the whole website
├── css/
│   └── style.css       ← theme (colors matched to the logo)
├── js/
│   └── main.js         ← mobile menu + small touches
├── assets/
│   ├── logo.png        ← your circular logo (from the uploaded file)
│   ├── favicon.svg     ← small pot icon shown in the browser tab
│   └── img/            ← food photos used on the site
│       ├── hero-thali.png
│       ├── chulha.png
│       ├── sarva-pindi.png
│       ├── natu-kodi.png
│       ├── jonna-rotte.png
│       ├── sakinalu.png
│       ├── biryani.png
│       └── mandi.png
├── .gitignore
└── README.md           ← this file
```

---

## How to put this on GitHub (free, ~10 minutes)

You will get a free website at
`https://YOUR-USERNAME.github.io/telangana-vantillu-eturnagaram/`

### Step 1 — Create a GitHub account (skip if you have one)

1. Go to <https://github.com/signup>
2. Sign up with your email and pick a username.

### Step 2 — Create a new repository

1. Click the **+** (top right) → **New repository**
2. Repository name: `telangana-vantillu-eturnagaram`
3. Keep it **Public** (required for free GitHub Pages)
4. **Do not** tick "Add a README" (we already have one)
5. Click **Create repository**

### Step 3 — Upload the files

**Easy way (no software needed):**

1. On your new empty repo page, click the link **"uploading an existing file"**
2. Drag the entire contents of this folder (all files and subfolders) into the browser window
   — or click **choose your files** and select everything
3. Click **Commit changes**

**OR using git on your computer (optional):**

```bash
cd telangana-vantillu-eturnagaram
git init
git add .
git commit -m "Telangana Vantillu Eturnagaram website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/telangana-vantillu-eturnagaram.git
git push -u origin main
```

### Step 4 — Turn on GitHub Pages

1. In your repository, go to **Settings**
2. In the left sidebar, click **Pages**
3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/(root)**
4. Click **Save**
5. Wait 1–2 minutes, then refresh — your site will be live at:

```
https://YOUR-USERNAME.github.io/telangana-vantillu-eturnagaram/
```

### Step 5 (optional) — Add your own domain

To use a custom domain (e.g. `telanganavantillu.com`): buy the domain
(~₹500–800/year from GoDaddy/Namecheap), then in **Settings → Pages →
Custom domain**, type the domain and save. Add the DNS records GitHub shows you.

---

## Updating the website later

### Change the menu, phone, hours, or text

Open `index.html` in any text editor (Notepad works), find the section,
edit the text, and re-upload the file (or commit and push if using git).

### Replace the food photos with real ones

Take photos of your dishes, name them the same as the existing files
(e.g. `biryani.webp` — a free converter like
[convertio.co](https://convertio.co/png-webp/) makes .webp files), and
replace the files in `assets/img/`.
Keep the same filenames and the website updates itself.

### Replace the logo

Replace `assets/logo.webp` and `assets/logo.png` with your logo files
(keep the same names).

---

## Placeholders to double-check

- **Hours** (index.html → "Hours" section): currently set to
  Mon–Fri 7:30 AM–10:00 PM and Sat–Sun 7:30 AM–10:30 PM. Edit to your real hours.
- **Menu & prices**: taken from the official menu PDF (Nov 2026). When prices
  change, update the "Menu" cards in index.html and/or replace
  `assets/menu.pdf` with the new PDF (compress it first if it is large —
  [ilovepdf.com/compress_pdf](https://www.ilovepdf.com/compress_pdf) works free).
- The photos are AI-generated illustrations; swap them for real restaurant
  photos whenever you like (keep the same filenames).

## Long-term maintenance

This is a **static site** — no frameworks, no build step, no database, nothing
to break or renew. It will keep working on GitHub Pages for free indefinitely.

To keep it healthy long term:

- Once a year, check the phone number, hours, and menu prices.
- Replace `assets/menu.pdf` whenever the printed menu changes.
- Keep the repository Public; GitHub Pages is free for public repos.
- Custom domain (optional): buy one (~₹500–800/yr), then
  Settings → Pages → Custom domain.

## Tech notes

- Pure HTML + CSS + JS. No frameworks, no build step.
- Responsive: works on phones, tablets and desktops.
- Local-business structured data (schema.org) for Google search/Maps.
- Open Graph tags for nice previews when shared on WhatsApp/Instagram.

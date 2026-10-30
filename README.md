# Telangana Vantillu — Eturnagaram Branch

Official website for the **Telangana Vantillu** restaurant, Eturnagaram branch
(Y Junction, Akulavari Ghanpur, Eturnagaram, Telangana 506165).

Built as a single static page — no build tools, no dependencies, no hosting cost.
Perfect for **GitHub Pages**.

- Main branch Instagram: <https://www.instagram.com/telangana.vantillu/>
- Eturnagaram branch Instagram: <https://www.instagram.com/telanganavantilluenr/>

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

## Updating the website later

### Change the menu, phone, hours, or text

Open `index.html` in any text editor (Notepad works), find the section,
edit the text, and re-upload the file (or commit and push if using git).

### Replace the food photos with real ones

Take photos of your dishes, name them the same as the existing files
(e.g. `biryani.png`), and replace the files in `assets/img/`.
Keep the same filenames and the website updates itself.

### Replace the logo

Replace `assets/logo.png` with your logo file (keep the name `logo.png`).

---

## Placeholders to double-check

- **Hours** (index.html → "Hours" section): currently set to
  Mon–Fri 7:30 AM–10:00 PM and Sat–Sun 7:30 AM–10:30 PM. Edit to your real hours.
- **Menu items**: a representative Telangana menu — adjust dishes to what you
  actually serve.
- The photos are AI-generated illustrations of Telangana dishes; swap them for
  real restaurant photos whenever you like.

## Tech notes

- Pure HTML + CSS + JS. No frameworks, no build step.
- Responsive: works on phones, tablets and desktops.
- Local-business structured data (schema.org) for Google search/Maps.
- Open Graph tags for nice previews when shared on WhatsApp/Instagram.

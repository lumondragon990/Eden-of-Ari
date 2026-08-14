# El Jardín de Ari 🌸

A daily-quote garden made for Ari. Light pink, peony petals, glassmorphism, and a new quote every day.

## What's inside
```
para-ari/
├── index.html      ← the entire app (HTML + CSS + JS in one file)
└── images/
    ├── ari-1.jpg
    ├── ari-2.jpg
    ├── ari-3.jpg
    └── ari-4.jpg
```

## Deploy to GitHub + Vercel (5 minutes)

### 1. Create the GitHub repo
1. Go to github.com → **New repository**
2. Name it `para-ari` (keep it **Private** if you don't want the photos public on GitHub)
3. Click **uploading an existing file** and drag in `index.html` AND the `images` folder
4. Commit

### 2. Deploy on Vercel
1. Go to vercel.com → **Add New → Project**
2. Import the `para-ari` repo
3. Framework preset: **Other** — no build settings needed
4. Click **Deploy**

Done. Vercel gives you a URL like `para-ari.vercel.app` to send her.

## Customizing
- **Quotes**: edit the `QUOTES` array in `index.html` — add your own lines, English or Spanish. The daily quote rotates automatically by date.
- **Photos**: drop more photos into `images/` and add their filenames to the `PHOTOS` array.
- **Colors**: everything lives in the `:root` variables at the top of the CSS.

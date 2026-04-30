# The Seeds of Wisdom

A landing page for **Khenpo Kunga Rinchen** and the young monks of **Rela Monastery Primary School** in Nangchen, Kham — an editorial-style site to share the school's story and invite support.

## 🚀 Deploy to GitHub Pages (3 steps)

1. Create a new repository on GitHub (e.g. `seeds-of-wisdom`).
2. Upload the contents of this folder to the repo (drag-and-drop in the GitHub web UI works fine).
3. Go to **Settings → Pages**, set **Source** to `Deploy from a branch` → `main` → `/ (root)` → **Save**.

Your site will be live at:
```
https://<your-username>.github.io/<repo-name>/
```

## 📁 What's inside

```
.
├── index.html          ← the entire site (single file, no build step)
├── images/             ← all photos & letter scans
│   ├── khenpo-large.jpg
│   ├── khenpo-portrait.jpg
│   ├── monastery-mountains.jpg
│   ├── young-monks.jpg
│   ├── monks-orange.jpg
│   ├── letter-sakya-trizin.jpg
│   ├── letter-monastery.jpg
│   └── letter-luding-khenchen.jpg
└── README.md
```

## ✏️ Editing the site

Everything lives in `index.html`. Common edits:

- **Change copy** → search for the section in plain English and edit the text.
- **Replace a photo** → drop a new image into `/images/` with the same filename, or change the `src=""` attribute.
- **Adjust colors** → at the top of the `<style>` block, edit the `:root { --paper, --maroon, --saffron, --teal ... }` variables.
- **Update donation tiers** → search for `<div class="tier"` and edit the four cards.
- **Hook up a real donation provider** → replace the `<a href="#contact">` button with a link to your PayPal / Stripe / bank-transfer instructions.

## 🎨 Design

- **Aesthetic**: editorial / sacred-manuscript — warm parchment background, monastic maroon, saffron and teal accents, deep serif typography (*Cormorant Garamond* + *EB Garamond*).
- **No build tools** — pure HTML / CSS / a few lines of vanilla JS. Loads fast, works on every browser.
- **Fully responsive** — looks great from phone to desktop.
- **Accessible** — semantic HTML, alt text on all images, respects `prefers-reduced-motion`.

---

*Sarva Maṅgalam* — May all be auspicious.

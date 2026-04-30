# 🌱 The Seeds of Wisdom

An editorial landing page for **Khenpo Kunga Rinchen** and the young monks of **Rela Monastery Primary School** in Nangchen, Kham — a remote Sakya school nestled among the highest peaks on Earth.

> *"Each child we educate is a lamp we light for the future, illuminating a world that needs more peace and wisdom."* — Khenpo Kunga Rinchen

---

## 🚀 Deploy to GitHub Pages — Step by Step

### 1. Create a new repository
- Go to [github.com/new](https://github.com/new)
- **Repository name:** `seeds-of-wisdom`
- **Public** (required for free GitHub Pages)
- ✅ Check **"Add a README file"**
- Click **Create repository**

### 2. Upload the files

⚠️ **CRITICAL: Upload files at the ROOT of the repository, not inside a subfolder.**

- On your repo page, click **Add file → Upload files**
- Drag `index.html`, `README.md`, **AND the entire `images` folder** into the upload box
- Scroll down → click **Commit changes**

After upload, your repo root must look exactly like this:

```
seeds-of-wisdom/
├── index.html          ← at the root
├── README.md
└── images/             ← folder with 8 .jpg files
    ├── khenpo-large.jpg
    ├── khenpo-portrait.jpg
    ├── letter-luding-khenchen.jpg
    ├── letter-monastery.jpg
    ├── letter-sakya-trizin.jpg
    ├── monastery-mountains.jpg
    ├── monks-orange.jpg
    └── young-monks.jpg
```

### 3. Turn on GitHub Pages
- Click **Settings** (top of repo)
- Left sidebar → **Pages**
- Under **Source** → select **Deploy from a branch**
- Branch: **`main`** · Folder: **`/ (root)`** → click **Save**

### 4. Visit your live site
After 1–2 minutes, a green banner will appear:

> ✅ *Your site is live at `https://<your-username>.github.io/seeds-of-wisdom/`*

Click the link. Done.

---

## ⚠️ If images don't load — read this first

GitHub Pages runs on Linux, which is **case-sensitive**. Your computer probably is not. This is the #1 reason images break.

The HTML expects all 8 image files to be named **exactly** like this — all lowercase, dashes between words, no spaces, no underscores:

| ✅ Correct | ❌ Wrong |
|------------|---------|
| `images/khenpo-large.jpg` | `images/Khenpo-Large.jpg` |
| `images/khenpo-portrait.jpg` | `images/khenpo_portrait.JPG` |
| `images/monastery-mountains.jpg` | `images/Monastery Mountains.jpg` |

**Quick test:** open this URL directly in your browser (replace `<username>`):
```
https://<username>.github.io/seeds-of-wisdom/images/khenpo-large.jpg
```
- ✅ Image loads → all good, hard-refresh your homepage with `Ctrl+Shift+R`
- ❌ 404 error → filenames don't match. Re-download this zip and re-upload the `images/` folder fresh.

**Built-in safety net:** any image that fails to load will show a red dashed box with the alt text, so you'll see exactly which file is the problem.

---

## ✏️ Editing the site

Everything lives in `index.html`. Common edits:

- **Change copy** — search for the text in `index.html` and edit it
- **Replace a photo** — drop a new image into `/images/` with the same filename
- **Adjust colors** — at the top of the `<style>` block, edit the `:root { --paper, --maroon, --saffron, --teal ... }` variables
- **Update donation amounts** — search for `<div class="tier"` and edit the four cards
- **Hook up a real donation provider** — replace the `<a href="#contact">` link with a PayPal / Stripe / bank-transfer URL

No build step, no dependencies, no framework. Edit, commit, refresh.

---

## 🎨 Design notes

- **Aesthetic** — editorial / sacred-manuscript: warm parchment background, monastic maroon, saffron and teal accents
- **Typography** — *Cormorant Garamond* (display) + *EB Garamond* (body) + *DM Mono* (small caps) via Google Fonts
- **Responsive** — looks great from phone to desktop
- **Accessible** — semantic HTML, alt text on all images, respects `prefers-reduced-motion`
- **Fast** — single HTML file, ~700 KB total including all images

---

## 📁 What's inside

```
.
├── index.html          ← the entire site (single file, no build step)
├── README.md           ← this file
└── images/             ← all photos & letter scans (8 files, lowercase names)
```

---

## 📜 Sections

1. **Hero** — Khenpo Kunga Rinchen's portrait, framed quote, headline
2. **Bio** — life story, the 116-volume Gyud She Kuntu, credentials
3. **Pull quote** — full-width contemplative passage
4. **The Place** — Rela Monastery in the high Himalayas
5. **The Children** — gallery of young monks at study and play
6. **Letters of Recognition** — three formal endorsements (Sakya Trizin, Rela Monastery, Luding Khenchen)
7. **How to Help** — four sponsorship tiers
8. **Contact** — message form

---

*Sarva Maṅgalam* — 🙏 May all be auspicious.

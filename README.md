# Matrika Now — Landing Page

A single-page website for **Matrika Now**, a spiritual healing and self-discovery platform led by Malvika. Built for GitHub Pages hosting.

---

## Live URL

After publishing, your site will be live at:

```
https://<your-github-username>.github.io/<repository-name>/
```

---

## How to Deploy on GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it (e.g. `matrika-now` or `healing`)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file

**Option A — Drag & drop (easiest):**
1. Open your new repository on GitHub
2. Click **Add file → Upload files**
3. Drag `index.html` into the upload area
4. Click **Commit changes**

**Option B — Git command line:**
```bash
cd "C:\Claude Projects\Websites\Healing"
git init
git add index.html
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

Your site will be live within ~1 minute at the URL shown at the top of the Pages settings.

---

## Tech Stack

| Item | Detail |
|------|--------|
| Framework | None — pure HTML, CSS, JavaScript |
| Fonts | Cormorant Garamond + Jost (Google Fonts) |
| Hosting | GitHub Pages (static) |
| Images | None (CSS gradient backgrounds) |
| File count | 1 (`index.html`) |

---

## Sections

1. Navigation
2. Hero
3. Ticker — Seven Matrikas
4. Why Matrika Now?
5. What We Offer
6. The Matrika Perspective
7. Discover Your Archetype
8. Understand Your Dosha
9. Ways to Work With Matrika Now
10. About Malvika
11. Start Your Journey
12. Footer

---

## Local Preview

```bash
cd "C:\Claude Projects\Websites\Healing"
python -m http.server 3000
```

Then open `http://localhost:3000` in your browser.

---

© 2025 Matrika Now

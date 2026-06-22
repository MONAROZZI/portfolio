# Mona Al-Rozzi — Portfolio Site

This folder contains your full portfolio website, ready to host for free on GitHub Pages.

## What's in this folder

- `index.html` — English version
- `index-it.html` — Italian version
- `editor.html` — a visual tool to prepare your photos (open this in your browser any time you want to add/change a photo)
- `photos/` — folder where your photos live (the site looks for exact filenames here)

## Step 1 — Put this on GitHub

1. Create a new repository on GitHub (e.g. name it `portfolio`). Keep it **Public** — Pages requires that on the free tier.
2. Upload all files in this folder into the repository, keeping the same structure (the `photos` folder included, even if empty for now).

## Step 2 — Turn on GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under "Build and deployment," set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` (or `master`) and folder to `/ (root)`. Save.
4. Wait about 1 minute. GitHub will show you a live link like:
   `https://your-username.github.io/portfolio/`

That link is now public — anyone can open it, no login needed.

- Your English homepage: `https://your-username.github.io/portfolio/index.html`
- Your Italian homepage: `https://your-username.github.io/portfolio/index-it.html`

(Optional: you can later point a real custom domain — like `monaalrazzi.com` — at this same GitHub Pages site, if you ever buy one. Not required to go live today.)

## Step 3 — Adding or changing photos

1. Open `editor.html` directly in your browser (just double-click the file, or visit it on your live GitHub Pages link).
2. For each project, click **Choose photo**, pick an image from your computer.
3. Click **Download** — this saves a correctly-named file like `portrait.jpg`.
4. On GitHub.com, open your repository → open the `photos` folder → click **Add file → Upload files** → drag in the downloaded photo(s) → commit.
5. Refresh your live site — the photo will now appear automatically in the right spot. No code editing needed.

**Important:** don't rename the downloaded files. The website looks for these exact names:

```
photos/portrait.jpg
photos/accessibility.jpg
photos/founders.jpg
photos/storytelling.jpg
photos/archive.jpg
photos/books.jpg
photos/crycare.jpg
```

## Updating text later

If you ever want to change wording, just ask Claude to edit `index.html` / `index-it.html` directly and re-share the updated files — you can then re-upload them to GitHub the same way (Add file → Upload files), replacing the old ones.

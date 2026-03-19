# 21not26

This is a single‑page invite site. Use `index.html` for hosting.

## Quick preview (local)

Open `index.html` in a browser, or run a tiny local server:

```zsh
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Hosting options (pick one)

### 1) GitHub Pages (fastest if you already use GitHub)
1. Create a new repo on GitHub (public or private).
2. Upload `index.html` to the repo root.
3. In **Settings → Pages**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/root`
4. Wait a minute for the published URL.

### 2) Netlify (drag‑and‑drop)
1. Go to `https://app.netlify.com/drop`.
2. Drag the folder containing `index.html` into the page.
3. Netlify gives you a public link immediately.

### 3) Vercel (import from Git)
1. Push this folder to a GitHub repo.
2. Go to `https://vercel.com/new` and import the repo.
3. Deploy with default settings; you’ll get a shareable URL.

## Notes
- Most static hosts look for `index.html` as the entry file.
- The file `21not26.html` is kept as the original copy.

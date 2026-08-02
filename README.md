# Mind Search

Search your own knowledge — a personal knowledge-capture prototype.

This is a single self-contained `index.html` file: no build step, no dependencies, no server required. It runs entirely in the browser.

## Deploy on Vercel

1. Push this repo to GitHub (see steps below).
2. Go to [vercel.com](https://vercel.com), sign in with GitHub.
3. Click **Add New → Project**, import this repo.
4. Framework preset: **Other** (no build command needed).
5. Click **Deploy**. Vercel will give you a live URL.

## Data storage

Entries are saved in the browser's local storage on whichever device/browser you're using — there's no shared backend yet, so data won't sync across devices. This is fine for solo testing; a real backend would be needed before multiple people use it together.

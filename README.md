# Michela Giorcelli — academic website

A small, fast, static website (no frameworks, no build step). Five pages:

| File | Page |
|------|------|
| `index.html` | Home / About |
| `research.html` | Publications & working papers |
| `teaching.html` | Courses |
| `cv.html` | CV (+ link to `cv.pdf`) |
| `contact.html` | Contact & profile links |
| `style.css` | Shared styling for every page |

---

## Editing the content

Everything is plain HTML — open any `.html` file in a text editor and change the
words between the tags. The files have comments (`<!-- like this -->`) pointing to
the parts you'll most likely want to change.

Common edits:

- **Add a publication** → in `research.html`, copy one `<div class="pub"> … </div>`
  block and change the year, title, venue, and links.
- **Add your photo** → put `headshot.jpg` in this folder, then in `index.html`
  replace `<div class="portrait"><span>MG</span></div>` with
  `<div class="portrait"><img src="headshot.jpg" alt="Michela Giorcelli"></div>`.
- **Add your CV PDF** → drop `cv.pdf` into this folder (the Download button already points to it).
- **Fix contact details** → edit `contact.html`.

A few things marked "replace with your own" (some CV rows, extra papers) are
placeholders so you can see the layout — swap in real content or delete them.

---

## Putting it online with GitHub Pages (free)

1. Create a free account at **github.com** if you don't have one.
2. Create a new repository. For a personal site, the simplest name is
   **`yourusername.github.io`** (e.g. `mgiorcelli.github.io`).
3. Upload every file in this folder to the repository
   (GitHub's web uploader: **Add file → Upload files** → drag them all in → **Commit**).
4. Go to the repo's **Settings → Pages**. Under "Build and deployment", set
   **Source = Deploy from a branch**, **Branch = main**, folder **`/ (root)`**, and Save.
5. Wait a minute, then visit **https://yourusername.github.io** — your site is live.

To update later: edit a file (locally or right in GitHub) and commit — the site
refreshes automatically within a minute or two.

### Optional: a custom domain
If you own a domain like `michelagiorcelli.com`, you can point it at the site in
**Settings → Pages → Custom domain**. Happy to walk you through this.

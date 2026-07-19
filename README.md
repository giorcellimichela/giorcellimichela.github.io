# Michela Giorcelli — academic website

A small, fast, static website (no frameworks, no build step) in a clean, minimal
style. Five pages, all sharing one stylesheet:

| File | Page |
|------|------|
| `index.html` | About / home (photo, name, short bio) |
| `research.html` | Research, grouped by theme |
| `teaching.html` | Courses |
| `cv.html` | CV (+ link to `cv.pdf`) |
| `contact.html` | Contact & profile links |
| `style.css` | Shared styling for every page |

---

## Adding your content

Everything is plain HTML — open a `.html` file in any text editor and replace the
text inside the brackets, e.g. `[Your title]`, `[Paper title]`. Anything in
`[square brackets]` is a placeholder waiting for your words. Comments
(`<!-- like this -->`) point to the parts you'll most likely change.

**Your photo** → put a file named `photo.jpg` in this folder, then in `index.html`
replace `<div class="photo"><span>MG</span></div>` with
`<div class="photo"><img src="photo.jpg" alt="Michela Giorcelli"></div>`.

**Your CV PDF** → drop `cv.pdf` into this folder (the links already point to it).

**Add a publication** → in `research.html`, copy one `<p class="paper">…</p>` line
and edit the title, journal, and links. Papers are grouped by theme — copy a whole
`<div class="theme">` block to start a new theme.

**Add a course** → in `teaching.html`, copy one `<li>` block.

**Links** (Google Scholar, NBER, CEPR, email) → search for `href="#"` and
`you@example.edu` and replace them.

Remove any leftover placeholder rows you don't need, and delete the grey
`note` boxes once a page is done.

---

## Putting it online with GitHub Pages (free)

1. Sign in at **github.com**.
2. Create a repository named **`yourusername.github.io`**.
3. Upload every file in this folder (**Add file → Upload files** → drag them in → **Commit**).
4. **Settings → Pages** → Source = *Deploy from a branch* → Branch = **main**, folder **`/ (root)`** → Save.
5. Wait ~1 minute, then visit **https://yourusername.github.io**.

To update later, edit a file and commit — the live site refreshes within a minute or two.

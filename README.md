# brentblackmon.github.io

Personal site: writing on AI, data, and operations, plus selected work.

## Publish this to GitHub Pages

The repo `brentblackmon/brentblackmon.github.io` is already created (empty, public) at
https://github.com/brentblackmon/brentblackmon.github.io — you just need to get these files into it.

**Easiest way (no git needed):**

1. Unzip the file you were sent.
2. Go to https://github.com/brentblackmon/brentblackmon.github.io/upload/main
3. Open the unzipped folder, select everything inside it (`index.html`, `writing.html`, `work.html`, `about.html`, `README.md`, `.nojekyll`, the `assets` folder, and the `writing` folder — all at once), and drag that whole selection onto the upload box. Dragging the files themselves (not the outer folder) keeps them at the top level of the repo, which matters for the links to work.
4. Scroll down and click **Commit changes**.
5. Give it a minute or two, then visit **https://brentblackmon.github.io**. GitHub Pages turns on automatically for a repo named `<username>.github.io` — no settings changes needed.

**If you'd rather use git**, from inside the unzipped folder:
```
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/brentblackmon/brentblackmon.github.io.git
git push -u origin main
```

## Updating later

Edit the HTML files, then:
```
git add .
git commit -m "Update"
git push
```
Changes go live a minute or two after pushing.

## File structure

```
index.html          Home
writing.html         Essay index
writing/*.html       Individual essays
work.html            Case studies / selected work
about.html           Experience timeline
assets/style.css     Shared styling
```

## Notes on content

- The four essays under `writing/` are rebuilt from three posts originally published on the WM Synergy site (all still under Brent's own byline there) plus one new piece, all rewritten as personal essays with the company product marketing and calls-to-action stripped out.
- All metrics on `work.html` come from Brent's own verified resume figures. If a number needs updating, edit the `.stat` blocks directly.
- Swap the "BB" circle avatar in `index.html` and `about.html` for a real photo by replacing the `.avatar` div with an `<img>` tag.

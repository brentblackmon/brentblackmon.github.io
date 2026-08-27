# brentblackmon.github.io

Personal site: writing on AI, data, and operations, plus selected work.

Every file here sits flat in one folder on purpose — no subfolders — so uploading
is just "select everything, drag it in," with nothing to get separated or left behind.

## Publish this to GitHub Pages

The repo `brentblackmon/brentblackmon.github.io` is already created (empty, public) at
https://github.com/brentblackmon/brentblackmon.github.io — you just need to get these files into it.

1. Unzip the file you were sent. You'll get one folder with 12 files in it, no subfolders.
2. Go to https://github.com/brentblackmon/brentblackmon.github.io
3. In the blue "Quick setup" box, click **"uploading an existing file"**.
4. Open the unzipped folder in File Explorer/Finder, click on one file, press **Ctrl+A** (or Cmd+A on Mac) to select all 12, then drag them onto the upload box on the GitHub page.
5. Scroll down and click the green **Commit changes** button.
6. Wait a minute or two, then visit **https://brentblackmon.github.io** — GitHub Pages turns on automatically for a repo named `<username>.github.io`, no settings changes needed.

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

Replace the files that changed and repeat the upload step (same drag-and-drop onto the
repo works for updates too — GitHub will ask you to confirm overwriting existing files).

Using git instead:
```
git add .
git commit -m "Update"
git push
```
Changes go live a minute or two after pushing.

## File structure

```
index.html                         Home
writing.html                       Essay index
data-was-always-the-point.html     Essay
the-analytics-gap.html             Essay
cost-of-standing-still.html        Essay
practical-ai.html                  Essay
work.html                          Case studies / selected work
about.html                         Experience timeline
style.css                          Shared styling
headshot.jpg                       Photo used on Home and About
.nojekyll                          Tells GitHub Pages to skip Jekyll processing
README.md                          This file
```

## Notes on content

- The four essay pages are rebuilt from three posts originally published on the WM Synergy site (all still under Brent's own byline there) plus one new piece, all rewritten as personal essays with the company product marketing and calls-to-action stripped out.
- All metrics on `work.html` come from Brent's own verified resume figures. If a number needs updating, edit the `.stat` or `.metric-compare` blocks directly.
- `headshot.jpg` is a small (100x100px) photo — fine for the current circular avatar size, but swap in a higher-resolution version if you ever want the photo larger anywhere.

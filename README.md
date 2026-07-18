# Pranay Nannuri — Portfolio

Single-file static portfolio. No build step, no dependencies (fonts
load from Google Fonts CDN).

## Deploy to GitHub Pages (recommended: clean URL)

1. Create a repo named exactly **`npkriami18.github.io`** on your
personal GitHub.
2. Put `index.html` (and `resume.pdf`, see below) at the repo root and push:
```bash
git init && git add . && git commit -m "portfolio"
git branch -M main
git remote add origin git@github.com:npkriami18/npkriami18.github.io.git
git push -u origin main
```
3. Done — live at **https://npkriami18.github.io** within a minute or two.
Alternative (any repo name, e.g. `portfolio`): push, then repo
**Settings → Pages → Source: Deploy from a branch → main / root**.
Site serves at `https://npkriami18.github.io/portfolio/`.

## Add your resume

Copy `Pranay_Nannuri_Resume.pdf` into the repo root and rename it
**`resume.pdf`** — the nav button and footer link point to it.

## Customizing

Everything lives in `index.html`:
- Colors: the `:root` CSS variables at the top (`--night`, `--signal`, etc.)
- Content: plain HTML sections (`#experience`, `#projects`, `#patent`,
`#skills`)
- The animated telemetry trace + cycling readouts: the first
`<script>` block (readout lines are in the `lines` array)
## After deploying

- Add the URL to your resume header, LinkedIn (website field +
Featured), and GitHub profile.
- Optional: buy a custom domain later and point it via Pages settings
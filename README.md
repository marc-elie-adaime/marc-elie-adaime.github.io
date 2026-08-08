# marc-elie-adaime.github.io

Personal academic website — Marc-Élie Adaime.

## How to publish (GitHub Pages)
1. Copy all files in this folder into the root of your repo
   `marc-elie-adaime/marc-elie-adaime.github.io`.
2. Commit and push. GitHub Pages serves `index.html` automatically at
   `https://marc-elie-adaime.github.io`.
3. Done — usually live within a minute.

## Files
- `index.html` — Home
- `research.html` — Research
- `publications.html` — Publications
- `cv.html` — CV
- `contact.html` — Contact
- `style.css` — shared styles
- `images/` — put your own photos here

## Replacing placeholder images
Photo placeholders currently load from picsum.photos. To use your own:
1. Add your photo to `images/` (e.g. `images/hero.jpg`).
2. In the HTML, replace the picsum URL with `images/hero.jpg`.
   - Hero background: in `index.html`, the `.hero-bg` block in the inline style / `style.css`.
   - Plate photos: each `<img src="https://picsum.photos/...">` — swap the src.
The scientific diagrams (pollen grain, phylogeny, sediment core) are inline SVG — no files needed.

## To add your CV PDF
Drop `cv.pdf` into the repo root; the "Download full CV" button already points to it.

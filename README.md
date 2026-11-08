# Ilya Hsieh-Jarov — Engineering Portfolio

Live site: https://ijarov.github.io

Plain HTML and CSS, no build step. GitHub Pages serves `index.html` directly (`.nojekyll` turns off Jekyll).

## Structure
- `index.html` — home page: intro, projects, experience, skills
- `enph-253.html`, `enph-259.html`, `enph-353.html` — project write-ups
- `style.css`, `site.js`, `favicon.svg`
- `fonts/` — self-hosted Barlow and Barlow Condensed (SIL Open Font License)
- `assets/` — compressed photos, videos, and diagrams
- `resume.pdf` — current resume

## Adding media
Commented-out `<figure>` blocks in `enph-259.html` and `enph-353.html` mark where a plot or screenshot would help. Put the file in `assets/`, uncomment the block, and update the file name and caption.

Keep photos under ~1600 px on the long side and videos short and muted (H.264 MP4) so pages load quickly on phones.

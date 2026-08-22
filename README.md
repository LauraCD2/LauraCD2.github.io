# lauracd2.github.io

Personal research page for Laura Camila Diaz-Delgado — computational imaging
and inverse problems, HDSP @ Universidad Industrial de Santander.

Live: https://lauracd2.github.io

## Structure

- `index.html` — the whole site (self-contained HTML + CSS + a little JS).
- `assets/laura.jpg` — portrait shown in the hero. Square-ish crop, ~600px works well.
- `assets/Laura_Diaz-Delgado_CV.pdf` — CV linked from the header and footer.
- `assets/frozen-clip-teaser.jpg` — teaser figure for the ECCV 2026 paper.
- `assets/Frozen-CLIP-Priors_ECCV2026_Poster.pdf` — conference poster.

## Updating

Adding a paper: copy one of the `<article class="pub">` blocks in the
Publications section. Adding news: add an `<li>` at the top of `ul.news`
(give it `class="new"` to colour the date magenta).

Accent colour lives in the `--magenta*` variables at the top of the stylesheet;
dark mode redefines the same names in two places.

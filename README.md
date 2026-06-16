# RadGrounder — project page

Project website for the MICCAI 2026 paper
**Scalable Training of Spatially Grounded 2D Vision–Language Models for Radiology**.

- Paper code: https://github.com/lmb-freiburg/RadGrounder
- Models: https://huggingface.co/lmb-freiburg/radgrounder

Static site (HTML/CSS/JS, no build step) served via GitHub Pages. The template is
adapted from [Nerfies](https://nerfies.github.io/) (Bulma-based academic project page),
following the layout of [radfinder.github.io](https://radfinder.github.io/).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push to the `radgrounder/radgrounder.github.io` repo (`main` branch). GitHub Pages
serves the site at https://radgrounder.github.io. `.nojekyll` disables Jekyll processing.

## Files

- `index.html` — the page content
- `overview.png` — Fig. 1, grounding-annotation pipeline
- `qualitative.png` — Fig. 2, qualitative report-generation example
- `paper.pdf` — the paper
- everything else — vendored template assets (Bulma, FontAwesome, jQuery, carousel/slider)

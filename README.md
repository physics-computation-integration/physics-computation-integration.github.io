# Physics + Computation website

Static GitHub Pages site for the proposed NSF IUSE project on integrating computation into undergraduate physics education.

## Content boundary

The website uses only the one-page project summary for project-level description. The full project description and the draft presentation remain local source material and are ignored by git. Do not add the full project description to this repository.

The current source documents confirm that 15 Ambassadors have been recruited, but do not provide their names or affiliations. Add those profiles to `ambassadors.html` once the list is available.

## Local preview

From this directory, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

This site is designed for the organization site repository `physics-computation-integration.github.io`. After the repository is created and the `main` branch is pushed, enable Pages from `Settings > Pages` with `Deploy from a branch`, branch `main`, folder `/ (root)`.

## Adding media

Put public media files in `assets/`, then add a linked card to `media.html`. Keep proposal-only documents out of the public repository.


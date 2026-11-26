# runetes.github.io

runetes.dev: the Runetes website, served from GitHub Pages.

A static page with no build step: `index.html`, `assets/style.css`, self-hosted
fonts under `assets/fonts/` (SIL OFL) and the rune logo `assets/rune.svg`.
`assets/og.png` is the social preview.

Preview locally:

```
python3 -m http.server 8123
```

Pushes to `main` deploy through `.github/workflows/pages.yml`. In the GitHub
repository settings, Pages must use "GitHub Actions" as its source and
`runetes.dev` as its custom domain; DNS points the apex at GitHub Pages.

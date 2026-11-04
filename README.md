# Will Kelly website

The source for [will-kelly.github.io](https://will-kelly.github.io/).

## Stack

- Hugo static site generator
- Plain CSS, no external theme
- GitHub Actions deployment to GitHub Pages

## Run locally

```bash
git clone https://github.com/will-kelly/will-kelly.github.io.git
cd will-kelly.github.io
hugo server -D
```

Open http://localhost:1313/.

## Publish

Commit and push to `main`. The GitHub Actions workflow builds and deploys automatically once the repository's **Settings > Pages > Build and deployment > Source** is set to **GitHub Actions**.

## Check

```bash
hugo --minify
git status
```

## Content

- `content/about.md`, `content/work.md`, `content/writing.md`: editable copy
- `layouts/`: HTML templates
- `static/css/site.css`: site styling
- `.github/workflows/hugo.yaml`: automated deployment

No custom domain has been configured. This is deliberate to avoid changing unrelated DNS or mail records.

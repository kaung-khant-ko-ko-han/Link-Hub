# KAUNG KHANT KO KO HAN — Hugo Profile Website

A professional one-page profile website built with [Hugo](https://gohugo.io/) and customized from the [LucentLink-Hugo](https://github.com/cx48/LucentLink-Hugo) starter. The design uses a warm paper texture, editorial typography, and tactile link cards for a personal analogue feel.

## Local development

Install Hugo Extended 0.149.0 or later, then run:

```bash
hugo server -D
```

Open `http://localhost:1313/` in a browser. The production build command is:

```bash
hugo --minify
```

## GitHub Pages

The included `.github/workflows/hugo.yml` builds and deploys the site automatically whenever changes are pushed to the `main` branch. In the repository settings, set **Pages → Source** to **GitHub Actions**. The configured production base URL is `https://kaung-khant-ko-ko-han.github.io/`; change `baseURL` in `hugo.toml` if the repository is hosted at a project subpath.

## Content updates

Edit `content/_index.md` to update the name, professional description, portrait path, social icons, link cards, or short “What I Do” section. Replace `static/images/profile.jpg` with a new image when needed. Styling is defined in `static/css/style.css`.

# CIC - Computer Information Exchange Association Personal Website Full-Stack Training Tutorial

This website is built using [vuepress](https://vuepress.vuejs.org/) and [vuepress-theme-plume](https://github.com/pengzhanbo/vuepress-theme-plume).

## Install

```sh
pnpm i
```

## Usage

```sh
# Start development server
pnpm docs:dev
# Build for production
pnpm docs:build
# Preview production build locally
pnpm docs:preview
# Update vuepress and theme
pnpm vp-update
```

## Deploy to GitHub Pages

The theme has already created GitHub Actions: `.github/workflows/docs-deploy.yml`. You also need to configure the following settings in your GitHub repository:

- [ ] `Settings > Actions > General`, scroll to the bottom of the page, under `Workflow permissions`, check `Read and write permissions`, and click the Save button

- [ ] `Settings > Pages`, under `Build and deployment`, `Source` select `Deploy from a branch`, `Branch` select `gh-pages`, and click the Save button
  (The `gh-pages` branch may not exist when first created. You can complete the above settings first, push code to the main branch once, and wait for GitHub Actions to complete before configuring this)

- [ ] Modify the `base` option in `docs/.vuepress/config.ts`:
  - If you plan to publish to `https://<USERNAME>.github.io/`, you can skip this step because `base` defaults to `"/"`.
  - If you plan to publish to `https://<USERNAME>.github.io/<REPO>/`, meaning your repository address is `https://github.com/<USERNAME>/<REPO>`, then set `base` to `"/<REPO>/"`.

If you need to use a custom domain, please refer to the [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)

## Documentation

- [vuepress](https://vuepress.vuejs.org/)
- [vuepress-theme-plume](https://theme-plume.vuejs.press/)
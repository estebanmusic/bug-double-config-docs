# Bloques Starter

A starter template for building documentation with [Bloques](https://bloques.app).

This repo is a working docs site. Clone it, connect it to Bloques, and replace the content with your own.

## Use this template

1. Select **Use this template** at the top of this repo on GitHub and create a new repository under your account or organization.
2. Sign in to [Bloques](https://bloques.app), create a site, and connect your new repository. Pick a publishing branch.
3. Edit pages in the Bloques editor in your browser, or edit `.mdx` files directly on GitHub. Every push to the publishing branch redeploys the site.

The first deploy starts as soon as the repository is connected.

## What's inside

```
.
├── docs.json                       # site name, navigation, theme, navbar
├── index.mdx                       # homepage
├── quickstart.mdx                  # onboarding walkthrough
├── essentials/
│   ├── writing.mdx                 # frontmatter, markdown, code, images
│   └── components.mdx              # built-in MDX components
└── configuration/
    ├── navigation.mdx              # groups and tabs in the sidebar
    └── theme.mdx                   # presets, primary color, navbar
```

## Make it yours

- Open `docs.json` and update `name`, `description`, and `navbar`.
- Replace the content of each `.mdx` file with your own.
- Edit the `navigation` array in `docs.json` to match your page structure.
- Pick a theme preset in `docs.json` under `theme.preset`.

See `quickstart.mdx` and the pages under `configuration/` for details.

## License

[MIT](./LICENSE)

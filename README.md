# Mehak Pahwa — Professional Portfolio

A personal professional portfolio presenting Mehak Pahwa's work across business operations, recruitment systems, cross-functional coordination, and digital marketing.

**Live website:** [mehak-pahwa-portfolio.mehakpahwa2828.workers.dev](https://mehak-pahwa-portfolio.mehakpahwa2828.workers.dev)

## About the website

The portfolio is designed around the idea of **bringing structure to the moving parts of business**. It presents experience and capabilities through visual systems, selected-work narratives, and an evidence-led professional journey rather than reproducing a résumé online.

## Technology

- [Astro](https://astro.build/) for the static website structure and build process
- TypeScript for safer, maintainable project code
- Plain CSS for the complete responsive visual system
- Minimal client-side JavaScript for navigation and progressive animation

The website is intentionally lightweight and suitable for deployment on Cloudflare Pages.

## Local development

Install the project packages:

```sh
pnpm install
```

Start the local development server:

```sh
pnpm dev
```

Then open the local address shown in the terminal, normally `http://localhost:4321`.

## Production build

```sh
pnpm build
```

Astro generates the deployment-ready website in the `dist` directory.

## Project structure

```text
public/                 Static assets and social preview image
src/components/        Reusable interface sections
src/data/portfolio.ts  Portfolio content
src/layouts/            Shared page layout and metadata
src/pages/              Website pages
src/styles/             Responsive design system
```

Most professional content can be updated in `src/data/portfolio.ts`. Structural homepage content is in `src/pages/index.astro`, and visual styling is in `src/styles/global.css`.

## Privacy

The public website and repository intentionally exclude Mehak's private address, telephone number, and personal résumé email. Environment files, generated builds, dependencies, and temporary working files are excluded through `.gitignore`.

## Deployment

The site is deployed through Cloudflare Workers with GitHub integration. Pushing an approved commit to the `main` branch triggers Cloudflare to build and publish the latest production version automatically.

## License

The source code and personal content in this repository are provided for Mehak Pahwa's portfolio. Personal text, branding, and visual assets may not be reused without permission.

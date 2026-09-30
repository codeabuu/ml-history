# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

## SEO & going live

SEO metadata lives in `index.html` (title, meta description, Open Graph, Twitter cards, JSON-LD structured data), with `public/robots.txt` and `public/sitemap.xml`.

The site URL is configured to `https://strikersite.vercel.app` in `index.html` (`canonical`, `og:url`, `og:image`, JSON-LD `url`/`@id`), `public/robots.txt` (`Sitemap:` line), and `public/sitemap.xml` (`<loc>`). Update these if the domain changes.

Before going live, add a 1200×630 image at `public/og-image.png` for link previews, then submit `sitemap.xml` in Google Search Console.

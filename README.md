# Hyssop Games — Website

Official "coming soon" landing page for Hyssop Games, an indie studio crafting casual games with fresh new mechanics.

Built with [Astro](https://astro.build) and [Tailwind CSS v4](https://tailwindcss.com), deployed as a static site via Cloudflare Pages.

## Project structure

```text
/
├── public/
│   ├── images/            # Logo assets, favicon
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── components/        # Hero, Manifesto, WaitlistForm, SiteNav, SiteFooter, etc.
│   ├── layouts/
│   │   └── Layout.astro   # Base HTML shell, fonts, meta tags
│   ├── pages/
│   │   └── index.astro    # Landing page
│   └── styles/
│       └── global.css     # Tailwind theme tokens + custom animations
└── package.json
```

## Waitlist signups

The "Notify me" forms submit directly to a [Kit](https://kit.com) (formerly ConvertKit) form — no backend required. Signups land in the Kit audience, ready to email when the game launches.

## Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                      |
| :----------------- | :------------------------------------------- |
| `npm install`       | Installs dependencies                         |
| `npm run dev`        | Starts local dev server at `localhost:4321`   |
| `npm run build`      | Builds the production site to `./dist/`       |
| `npm run preview`    | Previews the build locally, before deploying  |
| `npm run astro ...`  | Runs CLI commands like `astro add`, `astro check` |

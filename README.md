# LUMVIKO V2 — Frontend Prototype

A working Vite-based multilingual frontend prototype based on the supplied master prompt and logo reference.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To generate a deployment bundle, run `npm run build`.

## Implemented

- Homepage with the 10 requested sections (Home/Hero, Company, Projects, Services, Team, Process, FAQ, Contact, Footer plus navigation)
- Pricing page, inquiry form demo, service routes, portfolio and case-study placeholders
- Italian, English, Arabic UI language switching and Arabic RTL direction
- Dark/light/system preference, responsive layouts, mobile navigation, accordion interactions
- Original CSS motion and abstract visual effects; supplied logo used as visual reference and bundled in `assets/`
- Editable service, project and FAQ data in `src.js`

## Important limitations — NOT production complete

- This is an initial frontend prototype, **not** a fully implemented production site or a faithful implementation of every detail of the 30-section master prompt.
- No backend, real email sending, newsletter subscription, uploads or database; form only validates in demo mode.
- Case studies, team information, social/contact links and business facts require verified content.
- Copy is partly generic/placeholder and not all editorial text is fully localized. Legal documents and GDPR review are pending.
- SEO sitemap, full structured metadata, security headers, WCAG audit and performance testing still need implementation.
- Horizontal scrolling portfolio, video hero, sticky animated storytelling and custom process illustrations remain for later phases.
- The logo reference is a raster image. For an exact logo implementation, supply SVG or a transparent PNG. The temporary navigation symbol is CSS-based.

## Suggested next phase

Migrate to Next.js App Router with TypeScript and locale routes, finalize copy and brand assets, then implement the remaining interactions, legal/SEO layers and backend integrations.

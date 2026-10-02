# RCC Hampshire & Isle of Wight — Homepage Preview

A single-page redesign preview for the Division of Hampshire and Isle of Wight of the Masonic and Military Order of the Red Cross of Constantine.

## Scope

- Homepage only
- Prominent preview/concept banner
- Responsive desktop/tablet/mobile layout
- Cloudflare Workers static-assets configuration
- Links to the existing live site for deeper content while the preview is being evaluated
- No production cutover, CMS, authentication or forms in this phase

## Local preview

```bash
npm install
npm run dev
```

## Cloudflare Workers preview deployment

```bash
npx wrangler login
npm run deploy
```

The Worker name is currently `rcc-hants-iow-preview` so it remains clearly separate from the live website.

## Before production

1. Replace the concept-derived image crops with official, approved photography and the official RCC crest/logo.
2. Review all copy, titles and current events with the Division.
3. Add accessibility, performance and final SEO QA.
4. Only after approval should the production domain be mapped.

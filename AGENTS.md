## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)

## A.C.E Project Rules

- This repository contains SITE-001, the A.C.E Tailored main website.
- The live root rewrites to /beauty-preview/; src/pages/beauty-preview.astro controls it. Preserve the published Beauty visual direction.
- Preserve the premium, personal and elegant design.
- Brand colours: cream #f7f1e8, navy #102a3f and copper #c77d57.
- Headings use Playfair Display. Body and interface text use Montserrat.
- Use only verified business information. Never invent facts, services, reviews, results or claims.
- Current approved A.C.E Complete price: £179/month, 12-month initial commitment (£2,148), first £179 advance funds month one.
- Historical £399/£39 and £72.25 offers are SUPERSEDED; preserve historical immutable records, never restore them on active sales pages.
- No upfront website-creation fee. Preserve current legal hashes, non-VAT wording, native Beauty route and human controls.
- Approved primary CTA: “Get My Free Website Concept”.
- The seven-working-day promise must state that all required information, content and access must first be received.
- Keep layouts responsive and accessible.
- Before editing, inspect the relevant files and current Git status.
- Preserve existing user changes and avoid unrelated alterations.
- After code changes, run npm run build and report the result.
- Report every file changed and summarise the diff.
- Never commit, push, deploy or delete files unless Nicholas explicitly authorises it.
- Newer explicit commercial/launch approvals override historical rules. Do not change current production activation state through a site rebuild.

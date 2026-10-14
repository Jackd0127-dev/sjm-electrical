# SJM Electrical

An electrical-services portfolio concept using the approved SJM identity and Signal Grid Studio layout.

Keep the portfolio disclosure, noindex metadata, illustrative contact address and non-submitting form behavior.

## Local development

```sh
npm ci
npm run dev
```

Open the local URL printed by Vite.

## Commands

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server. |
| `npm run build` | Build the frontend and prepare the Sites output. |
| `npm run preview` | Preview the built frontend locally. |
| `npm run test:sites` | Run the existing Sites worker tests. |

## Files

- [`src/`](src/): frontend code and styles.
- [`public/`](public/): locally served assets.
- [`vite.config.mjs`](vite.config.mjs): existing build configuration.
- [`worker/`](worker/), [`scripts/prepare-sites-build.mjs`](scripts/prepare-sites-build.mjs) and [`.openai/hosting.json`](.openai/hosting.json): Sites serving and build support.
- [`tests/sites-worker.test.mjs`](tests/sites-worker.test.mjs): worker checks.

The build prepares `dist/client/index.html`, `dist/server/index.js` and `dist/.openai/hosting.json`. Keep the Sites support files intact; a successful build alone does not establish a deployed site.

## Project notes

- [Working instructions](AGENTS.md)
- [Asset credits](ASSET-CREDITS.md)
- [Design QA](design-qa.md)
- [Rebrand notes](REBRAND-NOTES.md)
- [Approved structural reference](design-source.png)

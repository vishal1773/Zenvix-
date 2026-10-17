# Welcome to your Lovable project

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Open your project in the [Lovable editor](https://lovable.dev) and keep building.

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: connect the project to GitHub and every change made in Lovable is committed straight to your repository.
- **Full ownership**: this code is yours. Push to your repository and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```

## Built with

- TanStack Start
- TypeScript
- React
- Tailwind CSS

## ZENVIX website — owner setup

Single-page site (TanStack Start + React + TypeScript). Enquiries are **not stored**; the form builds a message and hands it off to WhatsApp (or lets the visitor copy it).

### Configure (all in `src/config/business.ts`)
- [x] `whatsappNumber` — `919600311386` (country code + number, **digits only, no `+` or spaces**). Empty = "Copy enquiry message" fallback.
- [x] `officialPhone` — `+91 96003 11386`, dialled via `phoneHref: "tel:+919600311386"`
- [x] `officialEmail` — `zenvix2610@gmail.com` (linked as `mailto:zenvix2610@gmail.com`)
- [x] Final logo — uploaded artwork: `src/assets/zenvix-logo.png.asset.json` (footer, full lockup), `src/assets/zenvix-logo-header.png.asset.json` (header, emblem + name) and `public/favicon.png`
- [ ] Domain — connect a custom domain after publishing (Project Settings → Domains)

### Run / deploy
`bun install && bun run dev` locally; `bunx vitest run` for tests. Deploy with Lovable's Publish button.

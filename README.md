<img src="https://raw.githubusercontent.com/sahandsorouri/sahandsorouri/main/assets/banner.svg" alt="Sahand Sorouri" width="100%">

# QuoteScroll

Scroll your own Readwise book highlights in a full-screen vertical feed, instead of doomscrolling.

Live: [quotescroll.sorouri.com](https://quotescroll.sorouri.com)

## What it does

- Turns your Readwise highlights into a full-screen vertical feed: mouse wheel, keyboard (arrows, j, k) and touch.
- Browse by book, search by keyword, and mark favorites.
- Demo mode that works with no account.
- Your token stays in your browser and highlights live in IndexedDB on your device; nothing is stored on the server.
- A small server proxy talks to Readwise, so your token never goes to a third party.

## Run

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000). Use demo mode, or paste a Readwise token from [readwise.io/access_token](https://readwise.io/access_token).

Tests: `pnpm test` (Vitest) and `pnpm test:e2e` (Playwright).

Deploy to Cloudflare Pages with `pnpm pages:build`; see `DEPLOY_CLOUDFLARE.md`.

## Tech

Next.js 14, TypeScript, Tailwind CSS, IndexedDB (idb), Vitest, Playwright, MSW, Cloudflare Pages.

Not affiliated with Readwise.

---

Built by [Sahand Sorouri](https://sahand.sorouri.com) · platforms, bots and AI tools for businesses in Dubai.

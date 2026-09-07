# Crypto asset explorer

A routed React exercise that loads cryptocurrency asset data from CoinCap, displays an asset detail page, and saves selected asset IDs as favorites in localStorage.

**Collection:** React exercises · [Project directory](https://github.com/Rspinelli93/Rspinelli93/blob/main/PROJECTS.md)

## Stack

`react`, `react-dom`, `react-router-dom`, `vite`.

## Run locally

Install Node.js and npm, then run:

```bash
git clone https://github.com/Rspinelli93/react-coin.git
cd react-coin
npm install
npm run dev
```

Open the local URL printed by Vite. `npm run build` creates the production bundle and `npm run preview` serves that bundle locally.

## Available commands

| Command | Script in package.json |
| --- | --- |
| `npm run dev` | `vite` |
| `npm run build` | `vite build` |
| `npm run lint` | `eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0` |
| `npm run preview` | `vite preview` |

## Implementation notes

The source requests the CoinCap v2 API. API availability and authentication requirements need to be checked before running; no live market-data service is bundled.

## Repository guide

- [`index.html`](index.html)
- [`package.json`](package.json)
- [`src/`](src/)
- [`vite.config.js`](vite.config.js)

---

[Back to my GitHub profile](https://github.com/Rspinelli93)

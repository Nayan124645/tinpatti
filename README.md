# Teen Patti — Table Edition

A local, single-device Teen Patti game for 2–4 people.

## Run locally

1. Install Node.js (LTS).
2. Extract this project.
3. Open a terminal in the project folder.
4. Run:

```bash
npm install
npm run dev
```

5. Open the local URL printed by Vite.

## Build for hosting

```bash
npm run build
```

Upload the generated `dist` folder to a static host such as Vercel or Netlify.

## Rules implemented

- Three random cards per player.
- Normal mode: all cards stay hidden until the central Reveal All button is pressed.
- Blind mode: each player can privately view their own cards once. The hand is hidden and locked when they continue. Reveal All stays disabled until every player has viewed.
- Reveal All exposes every hand simultaneously and calculates the best hand.
- Ties are supported.

This is a casual, virtual-points-free implementation. No betting, deposits, or real-money features.

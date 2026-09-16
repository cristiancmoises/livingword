# <img src="https://github.com/realvincentuche/reactive-bible/blob/e5236e18b12fced36c379a71dcf9597960986c68/public/icon.svg" alt="Logo" height="30" /> Reactive Bible

This is a [Reactjs](https://react.dev/) project bootstrapped with [`Vitejs`](https://vitejs.dev).

A Reactive Bible App developed with Reactjs & Mantine. Features include:

- Light and Dark Mode.
- Browser localstorage for saving app states and mode.
- Robust autocomplete search with key stroke events.
- Bible verse scroll-to-view feature.
- Offline Bible passages.
- Online Audio Bible.
- Book, Chapter & Verse Navigation.
- Prev & Next Chapter navigation. 
- Detailed tests included using react testing library and vitest.
- And lots more.

Libraries used include:

- Mantinejs
- Tabler icons for react
- Howler js as audio player
- Zustand for state management
- And lots more

Audio Bible streaming from [`Wordpocket`](https://wordpocket.org)

Get a preview at:
<a href="https://reactive-bible.vercel.app" target="_blank">reactive-bible.vercel.app</a>

![alt text](https://github.com/realvincentuche/reactive-bible/blob/928ba523de0697e13a23030b2b9bd3295bbc0dc8/public/reactive-bible.png)

## Getting Started

Use Node.js 22.12 or later and the committed npm lockfile.

```bash
npm ci --no-audit --no-fund
npm run dev
```

Run the build and tests before submitting changes:

```bash
npm run build
npm test
npm run coverage
```

`npm test` runs once and exits. Use `npm run test:ui` for the interactive Vitest UI. Coverage uses the V8 provider; generated reports are ignored by Git.

Your feedback and contributions are welcome!

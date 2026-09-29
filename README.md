# Fake or Real?

A scam-spotting card game for families. Players see realistic texts, emails, DMs, pop-ups, push notifications and URLs, and decide whether each one is **Fake** or **Real**. Every card reveals the clues and a one-line lesson.

- **Decks:** All, Kids, Teens, Parents
- **Round length:** Quick 10, 25, or the whole deck (69 cards)
- **Modes:** *Play on my phone* (solo, with score and streak) or *Play as a room* (big-screen mode with two teams)

The whole game is one static file, `index.html`, with no build step and no dependencies. The only external request is for Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy to Vercel

1. In Vercel, choose **Add New → Project** and import this GitHub repo.
2. Set **Framework Preset** to **Other**. Leave the build command and output directory empty.
3. Click **Deploy**.

Or from the CLI: `npx vercel` (preview) and `npx vercel --prod` (production).

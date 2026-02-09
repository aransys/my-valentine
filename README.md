# u + me?

A playful Valentine’s Day app: tap the heart to grow it, fill the love bar, and get your answer. One HTML file, no build step.

## How it works

1. **Tap the heart** — Each tap makes it grow, shows a short message, and fills the love bar.
2. **At 16 taps** — The **Yes** and **Maybe** buttons appear.
3. **Yes** — Success screen with confetti. Tap the success area for more confetti.
4. **Maybe** — Click 3 times (text changes: "idk…", "don't look at me", "wait"). On the 4th click it turns into **yes duh** — click that for success.
5. **Secret** — After the buttons appear, rapidly tap the heart 6 times. It **pops** with a burst animation and a special ending.

## Features

- Growing heart with smooth animations
- Love bar that fills as you tap
- Confetti (canvas-confetti)
- Haptic feedback on supported devices
- Mobile-friendly layout (thumb-reach optimized)
- Reduced motion support
- Single file, no dependencies except CDN scripts

## Run it

Open `index.html` in a browser, or:

```bash
npx serve .
```

## Tech

- Vanilla HTML, CSS, JavaScript
- Inter font (Google Fonts)
- Canvas Confetti
- Works on desktop and mobile

# Thai Surprise 🌶️ — Spicy Invaders

A bite-sized, **Space Invaders–style** arcade game with a **Thai surprise** theme.
A wave of fiery chillis is descending on your street-food cart — blast them with
chilli seeds before they reach your wok!

It's a **single, self-contained `index.html`** — no build step, no dependencies,
no servers. Open it and play instantly, on **mobile or desktop**.

## ▶️ Play now

- **Hosted on GitHub Pages:** once Pages is enabled (see below), play at
  `https://mrkyle7.github.io/thaisuprise/`
- **Locally:** just open `index.html` in any browser, or double-click it.

## 🎮 Controls (simple & mobile-friendly)

| Action | Mobile | Desktop |
| ------ | ------ | ------- |
| Move   | **Drag** anywhere on screen | **← / →** (or **A / D**) |
| Fire   | **Tap & hold** (auto-fires) | **Space** (or **↑ / W**) |
| Start / restart | Tap the button | Tap the button or **Enter** |

That's it — one finger to play.

## 🌶️ How to play

- **🌶️ Red / 🫑 green chillis** drop in formation and march toward your cart.
  Shoot them for points.
- **🧄 Garlic** bulbs are tougher — they take two hits.
- Fill the **Spice Meter** by destroying chillis to unleash **🔥 Spicy Power**:
  rapid twin-stream fire for a few seconds.
- Catch a falling **🥭 mango** to cool down, score a bonus, and trigger power fire.
- You have three lives (🌶️🌶️🌶️). Don't let the chillis reach your wok, and
  dodge the falling spice drops. Each wave gets faster and hotter.

Your **best score** is saved locally in your browser.

## 🚀 Enabling GitHub Pages (one-time)

The included workflow (`.github/workflows/pages.yml`) deploys the site
automatically on every push. To turn it on:

1. Go to the repo's **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Push (or re-run the workflow) and the game goes live at the Pages URL.

## 🛠️ Tech

- Plain HTML5 `<canvas>` + vanilla JavaScript (no frameworks).
- Resolution-independent rendering that scales to any screen.
- Emoji-based sprites, so it looks great everywhere with zero image assets.

Enjoy, and mind the heat! 🌶️🔥

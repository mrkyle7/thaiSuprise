# Thai Surprise 🌶️ — Spicy Invaders

<p align="center">
  <a href="https://mrkyle7.github.io/thaiSuprise/">
    <img alt="Play Thai Surprise" src="https://img.shields.io/badge/%E2%96%B6%20PLAY%20NOW-Thai%20Surprise%20%F0%9F%8C%B6%EF%B8%8F-e01b00?style=for-the-badge&labelColor=2a0d0d" />
  </a>
</p>

<p align="center">
  <b><a href="https://mrkyle7.github.io/thaiSuprise/">👉 mrkyle7.github.io/thaiSuprise 👈</a></b>
</p>

A bite-sized, **Space Invaders–style** arcade game with a **Thai surprise** theme.
A wave of fiery chillis is descending on your street-food cart — blast them with
chilli seeds before they reach your wok!

It's a **single, self-contained `index.html`** — no build step, no dependencies,
no servers. Open it and play instantly, on **mobile or desktop**.

## ▶️ Play now

- **▶️ [Play in your browser](https://mrkyle7.github.io/thaiSuprise/)** — `https://mrkyle7.github.io/thaiSuprise/`
  (live once Pages is enabled; see [setup](#-enabling-github-pages-one-time) below).
- **Locally:** just open `index.html` in any browser, or double-click it.

## 🎮 Controls (simple & mobile-friendly)

| Action | Mobile | Desktop |
| ------ | ------ | ------- |
| Move   | **Drag** anywhere on screen, or **📱 tilt** the phone | **← / →** (or **A / D**) |
| Fire   | **Tap & hold** (auto-fires) | **Space** (or **↑ / W**) |
| 3D mode | Flip the **🕶️ 3D Immersive** toggle | Toggle, or press **3** anytime |
| Pause / Quit | **⏸** / **✕** buttons (top-right) | **P** / **Esc** to pause |
| Start / restart | Tap the button | Tap the button or **Enter** |

That's it — one finger (or a tilt) to play.

## 📱 Tilt / Gravity Steering

Flip the **📱 Tilt Steering (Gravity)** toggle on the start screen to steer with
your phone's motion sensor: hold the phone however feels comfortable and **lean
it left or right** to slide your wok. The resting angle is **auto-calibrated**
each time a round starts, so you don't have to hold it perfectly flat, and a
small dead-zone keeps it steady. Touch-dragging always overrides tilt if you
grab the screen. On iOS the browser asks for motion permission the first time
(tap **Allow**); if a device has no motion sensor it quietly falls back to
touch/keys. Your choice is remembered between sessions.

## 🕶️ 3D Immersive Mode

Flip the **🕶️ 3D Immersive Mode** toggle on the start screen (or press **3**
at any time) to drop into a first-person-style perspective: the chilli swarm
**looms down a corridor straight at your wok**, spice drops rush toward you and
swell as they approach, and a perspective grid floor + warp-speed starfield pull
you into the heat. Same controls, same gameplay — just a lot more in-your-face.
Your choice of 2D / 3D is remembered between sessions. It's all rendered with a
tiny custom perspective projector, so there are **still zero dependencies**.

## 🌶️ How to play

- **🌶️ Red / 🫑 green chillis** drop in formation and march toward your cart.
  Shoot them for points.
- **🧄 Garlic** bulbs are tougher — they take two hits.
- Fill the **Spice Meter** by destroying chillis to unleash **🔥 Spicy Power**:
  rapid twin-stream fire for a few seconds.
- A **🛺 golden tuk-tuk** flies across the top now and then. **Shoot it down**,
  then **grab the 🌶️🔥 token it drops** to trigger **🐉 Dragon Breath** — a
  temporary superpower with a rapid **5-way fiery spread shot** *and*
  invincibility for ~8 seconds. (So you can earn it by shooting **and** catching!)
- Catch a falling **🥭 mango** to cool down, score a bonus, and trigger power fire.
- **Boss fight:** every **5 armies** you clear, a **🌶️👹 ginormous Chilli Monster**
  appears — it sweeps across the top and spits **double-size fireballs**. Whittle
  down its health bar to drop big points (plus a mango and a Dragon Breath token).
- You have three lives (🌶️🌶️🌶️). Don't let the chillis reach your wok, and
  dodge the falling spice drops. Each wave gets faster and hotter.

Your **best score** is saved locally in your browser.

## 🚀 Enabling GitHub Pages (one-time)

Because the game is a single static `index.html`, the simplest hosting is
**classic branch-based Pages** — no build, no workflow:

1. Go to the repo's **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set **Branch: `main`**, folder **`/ (root)`**, then **Save**.
4. Wait ~1 minute — the game goes live at `https://mrkyle7.github.io/thaiSuprise/`.

## 🛠️ Tech

- Plain HTML5 `<canvas>` + vanilla JavaScript (no frameworks).
- Two renderers from one game loop: a 2D classic view and a custom
  perspective-projected **3D** view — no WebGL, no Three.js, no CDN.
- Resolution-independent rendering that scales to any screen.
- Emoji-based sprites, so it looks great everywhere with zero image assets.

Enjoy, and mind the heat! 🌶️🔥

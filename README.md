<div align="center">

# 🪰 A Mosquito and a Truck

### *an existential crisis in 6 acts*

**[▶ Play it live](https://jorge-polanco-roque.github.io/el-mosco/)**

<br>

<img src="docs/screenshot.png" alt="A Mosquito and a Truck — title screen" width="820">

**A cute-brutal interactive story.** Kawaii pastel visuals as a Trojan horse for the abyss.
You advance by completing challenges — each one *makes you feel* a stage of the crisis in your own hands.

<br>

[![three.js](https://img.shields.io/badge/three.js-r160-000000?style=flat-square&logo=three.js&logoColor=white)](https://threejs.org)
[![Web Audio](https://img.shields.io/badge/Web%20Audio-chiptune-df48ef?style=flat-square)](https://developer.mozilla.org/docs/Web/API/Web_Audio_API)
[![No build](https://img.shields.io/badge/build-none-9984e8?style=flat-square)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-007aff?style=flat-square)](LICENSE)

<br>

**🌐 Read this in your language**

**English** · [Español](README.es.md) · [Português](README.pt.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [中文](README.zh.md)

</div>

---

> *One instant it was buzzing. The next: nothing. The universe didn't blink.*

A mosquito crosses a highway for no reason. A truck passes. The mosquito ceases to exist.
That microsecond — an absolute, absurd death with no witnesses and no meaning — detonates
the question we all carry: **if that life meant nothing, what makes mine different?**

This project *is* that reflection, turned into a game. The tenderness of the art carries the
weight so the words don't have to shout. **The contrast is the work.**

---

## 🎭 The six acts

Each challenge embodies its idea *mechanically* — the meaning isn't explained, it's played.

| # | Act | Challenge | The truth it lands |
|:-:|-----|-----------|--------------------|
| 0 | **The Detonator** | Save the mosquito before the light arrives | Impossible by design. *"And what if you were the mosquito?"* |
| 1 | **Insignificance** | Find *yourself* among hundreds of identical dots | *"None was special. Neither are you. And yet, here you are, still looking."* |
| 2 | **The Absurd** | Push the rock to the summit (it always rolls back) | Camus: *"The struggle itself toward the heights is enough to fill a heart."* |
| 3 | **The Vertigo of Freedom** | Choose one door — the others vanish forever | *"Every yes is a thousand noes. That is what living is."* |
| 4 | **Being-toward-Death** | Keep it alive (it fades faster than you can sustain) | Heidegger: *"Death is not the enemy. It's the frame."* |
| 5 | **The Revolt** | Build something — leave your mark | *"Meaning isn't found. It's made."* → **"One must imagine the mosquito happy."** |

---

## ✨ Features

- **Cute-brutal aesthetic** — pastel floating blobs, comic outlines, a hand cursor, cel-shaded 3D.
- **Six interactive mechanics** — every act is a different, symbolic mini-game.
- **Adaptive chiptune score** — synthesized live in A-minor. A low-pass filter closes as you
  descend: bright at the start, choking in *Death*, luminous again in *The Revolt*.
- **Reactive sound design** — the mosquito's **zap**, tension **risers** on every transition,
  and randomized **selection SFX** so nothing ever repeats.
- **Zero build, zero assets, zero tracking** — one self-contained HTML file.

## 🎮 Controls

| Input | Action |
|-------|--------|
| **Click / tap** | Advance · interact · make a choice |
| **Drag** | Push the rock (Act 2) |
| **M** | Mute / unmute music |
| **R** | Revive — restart from the end |

## 🛠️ Tech stack

- **[three.js](https://threejs.org)** (r160) — `MeshToonMaterial` cel-shading, inverted-hull comic outlines.
- **Web Audio API** — a tiny live chiptune engine (oscillators, filters, procedural SFX). No audio files.
- **Vanilla JS + HTML/CSS** — a single-file finite state machine. No framework, no bundler.

## 🚀 Run locally

No build step. Any static server works:

```bash
git clone https://github.com/Jorge-Polanco-Roque/el-mosco.git
cd el-mosco
python3 -m http.server 8000
# open http://localhost:8000
```

> Music starts on your first click (browser autoplay policy).

## 📁 Project structure

```
el-mosco/
├── index.html          # ← the experience (6 acts, music, SFX)
├── demo/
│   └── toy-world.html  # the playful sandbox it grew from
├── docs/
│   └── CONCEPT.md       # artistic & technical design document
└── README*.md           # this, in 6 languages
```

## 🌱 Origin & credits

- **Visual style** reverse-engineered from the wonderful [ketakuma.com](https://ketakuma.com)
  using [skillui](https://www.npmjs.com/package/skillui) (static design-token extraction).
  This is a *reinterpretation of style*, not a copy of any assets.
- **Philosophy** in the margins: Albert Camus (*The Myth of Sisyphus*), Martin Heidegger
  (*being-toward-death*), Søren Kierkegaard & Jean-Paul Sartre (the dread of freedom).
- **Typeface**: [Londrina Solid](https://fonts.google.com/specimen/Londrina+Solid).

## 📄 License

[MIT](LICENSE) — do something with it. That's the whole point of Act 5.

<div align="center">
<br>

*Meaning isn't found. It's made.*

**One must imagine the mosquito happy — and you too.**

</div>

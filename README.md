# Code & Throttle (`codeandthrottle.in`)

> **High-performance backend architecture by day. Open-throttle twisties on the weekends.**

A zero-dependency, ultra-lightweight web portal bridging systems software engineering and mechanical motorcycle culture. Built with pure HTML5, vanilla JavaScript, Tailwind CSS via CDN, and custom CSS design tokens.

---

## ⚡ Overview

Code & Throttle documents two parallel engineering pursuits:
* **The Code:** Enterprise Java, Spring Boot, distributed data design, concurrency, and client-side web tooling.
* **The Throttle:** Road telemetry, dyno runs, suspension physics, motorcycle electronics retrofitting, and touring logs through the Western Ghats.

The site uses a terminal-inspired, hardware-meets-IDE visual system featuring high-contrast dark surfaces, tachometer amber and telemetry cyan accents, live typewriter loops, client-side category filtering, and interactive code windows.

---

## 🛠️ Features

* **Zero-Dependency Runtime:** Runs directly in any modern browser without npm, node packages, or build steps.
* **Dynamic Theme Switcher:** 3 distinct presets (`dark`, `light`, and scanline `cyber`) with custom CSS variables and keyboard shortcut support (`T` to cycle).
* **Interactive Category Filtering:** Instantly filters feed entries between **Code** and **Throttle** logs using vanilla JS DOM transforms.
* **Interactive Telemetry Window:** Synthesized syntax highlighting featuring an immutable Java 21 telemetry parsing record with instant clipboard copy.
* **Ambient Interactivity:** Reading progress indicator, cursor tracking radial glow, and intersection-observer scroll reveals.

---

## 🎨 Theme Tokens & Color Palette

| Token | Dark Mode (Default) | Light Mode | Cyber Mode | Design Role |
| :--- | :--- | :--- | :--- | :--- |
| `--bg` | `#0b0c10` | `#f5f4ef` | `#030712` | Main viewport canvas |
| `--accent` | `#ff6b00` | `#d35400` | `#ff0055` | Tachometer Amber / Shift-light Orange |
| `--accent-2` | `#00d2ff` | `#007799` | `#00f2fe` | Telemetry Cyan / Anodized Titanium |
| `--card` | `#13151b` | `#ffffff` | `#06111f` | Elevated card surfaces |
| `--code-bg` | `#07080b` | `#1a1b1e` | `#010409` | Deep contrast editor wells |

---

## 📁 Project Structure

```text
code-and-throttle/
├── index.html        # Complete, single-file portal (UI, CSS tokens, and scripts)
├── assets/           # Optional local static assets (favicons, route GPX files, diagrams)
└── README.md         # Architecture blueprint and deployment guide

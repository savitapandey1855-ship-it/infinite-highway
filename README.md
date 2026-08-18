# 🏎️ Infinite Highway

A 3D car driving game built with **Three.js** that loads your `american_road.glb` city model and tiles it infinitely — the road keeps generating ahead of you as you drive, so you never run out of road.

## 🎮 Play

👉 **[Play the game](https://savitapandey1855-ship-it.github.io/infinite-highway/)**

## 🕹️ Controls

| Key | Action |
|-----|--------|
| `W` / `↑` | Accelerate |
| `S` / `↓` | Brake / Reverse |
| `A` / `←` | Steer Left |
| `D` / `→` | Steer Right |
| `Space` | Handbrake |
| `C` | Switch Camera (Chase / Hood / Cinematic) |

## ✨ Features

- **Infinite road tiling** — 5 road tiles are kept active at all times; as you drive past one, it's recycled to the front, creating an endless highway
- **Realistic car physics** — acceleration, braking, drag, speed-dependent steering, handbrake
- **3 camera modes** — chase cam, cockpit/hood view, and cinematic far view
- **Live HUD** — speedometer with arc gauge, gear indicator, distance counter, top speed tracker, score
- **Dynamic shadows** — sun follows the car for real-time shadow casting
- **Built from your 3D model** — the American Road GLB is loaded and cloned to create the infinite road

## 🛠️ Tech

- [Three.js](https://threejs.org/) r160 (loaded via CDN)
- GLTFLoader for the 3D model
- Pure vanilla JS — no build step, no dependencies
- Hosted on GitHub Pages

## 📦 Model Credit

American Road model by **jimbogies** on Sketchfab (CC-BY-4.0).
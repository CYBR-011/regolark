# regolark

A dark neon-themed Ragnarok Online hub page — single HTML file, no dependencies, no server needed.

---

## Features

**Design**
- Dark neon aesthetic with animated flickering gradient logo
- VT323 pixel font + Share Tech Mono monospace throughout
- Ambient colored background glow (teal, purple, green)
- Fully self-contained — one `.html` file with all assets embedded

**Navigation — Game Links**
Clickable neon-colored links, each grouped by color:

| Link | Color |
|---|---|
| ROX Global, ROX SEA | Cyan |
| ROMC Global, ROMC SEA, ROMC Taiwan | Gold |
| RONW | Green |
| ROOC | Purple |
| Korean RO's | Red |

**App Icon Strip**
Eight clickable app icons with neon hover glow, left to right:

| App | Link |
|---|---|
| Mumu Player | mumuplayer.com |
| LD Cloud | Google Play |
| Red Finger | Google Play |
| UG Phone | Google Play |
| OS Link | oslink.io |
| Auto Clicker | Google Play |
| Image Clicker | Google Play |
| Macrorify | Google Play |

**Chibi Characters**
- Two 3D chibi archer figures on left and right sides
- Full 360° rotation — both always face the cursor/touch point
- Gentle floating bob animation
- Draggable — click and drag anywhere on screen, stays where dropped
- Black background removed from character images via canvas pixel processing

**Arrow Shooting**
- Both chibis shoot flaming arrows toward the cursor/finger
- Fires every 400ms, speed 56px/frame
- Arrow spawns from the bow flame tip with a muzzle burst flash effect
- Arrow rendered with shaft, golden arrowhead, flame glow, sparks, and cyan feather tail
- Arrows fade out on impact

**Background Music**
- Prontera Theme (Ragnarok Online OST) embedded as base64 audio
- Loops continuously at 150% volume via Web Audio API GainNode
- Autoplays on page load; falls back to first user click if browser blocks autoplay

---

## Usage

1. Download `regolark.html`
2. Open it in any modern browser — no install, no server required
3. Move your mouse/finger to aim the chibis
4. Click and drag either chibi to reposition them

---

## File Structure

```
regolark.html   — everything in one file
README.md       — this file
```

---

## Tech Stack

- Pure HTML / CSS / JavaScript — zero frameworks
- Web Audio API — for 150% volume boost
- Canvas API — character background removal + arrow rendering
- Google Fonts — VT323, Share Tech Mono
- All images and audio embedded as base64

---

## Links Referenced

| Game | URL |
|---|---|
| ROX Global | ragnarokx.net |
| ROX SEA | ragnarokx.com |
| ROMC Global | Google Play |
| ROMC SEA | ragnaroketernallove.com |
| ROMC Taiwan | Google Play |
| RONW | gnjoy.hk |
| ROOC | Google Play |
| Korean RO's | gravity.co.kr |

---

https://cybr-011.github.io/regolark/

© 2026 regolark

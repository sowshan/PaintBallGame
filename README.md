# 💥 Paintball Smash

A fast-paced browser game — paintballs fly across the screen and you have to tap/click them before they escape. Survive as long as you can, build combos, and climb the leaderboard!

🎮 **[Play it live](#)** ← replace with your GitHub Pages link after setup

---

## 🕹️ How to Play

- **Tap or click** paintballs to smash them before they leave the screen
- You have **3 hearts** — miss a ball and you lose one
- Game over when all hearts are gone
- The game gets progressively harder over time
- Build **combos** by hitting balls back-to-back for bonus points
- Hit a **10x combo** to trigger a brief slow-motion window

### Special balls
| Ball | Effect |
|---|---|
| ⭐ Golden | Bonus points |
| 💣 Bomb | Pops every ball currently on screen |
| ☠️ Decoy | Costs you a heart if tapped — avoid it! |
| 👑 Boss | Larger ball, needs 3 hits to pop |

### Power-ups
| Power-up | Effect |
|---|---|
| ❄️ Freeze | Slows everything down for a few seconds |
| 💣 Bomb | Clears all balls and awards points |
| 🛡️ Shield | Blocks the next miss |

---

## 🎨 Themes

Choose from 8 visual themes, each with its own colour palette and pop animations:

Default · Christmas · Halloween · Black & White · Ocean · Neon · Fire · Galaxy

Your selected theme is saved in your browser for next time.

---

## 🏆 Leaderboard

Your top scores are saved locally in your browser (top 10, ranked by score). Enter your name before each run to track your results.

> Note: the leaderboard is currently per-device (browser `localStorage`). It does not sync across devices.

---

## 🚀 Running it yourself

This is a single self-contained HTML file — no build step, no dependencies, no server required.

### Option 1 — Just open it
Download `index.html` and open it in any browser (desktop or mobile).

### Option 2 — Host it for free with GitHub Pages
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Your game will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

---

## 🛠️ Tech

- Plain HTML5 Canvas + vanilla JavaScript — no frameworks, no build tools
- Responsive to any screen size, accounts for device pixel ratio (crisp on retina/high-DPI displays)
- Haptic feedback on supported mobile devices

---

## 📄 License

MIT — see [LICENSE](LICENSE)

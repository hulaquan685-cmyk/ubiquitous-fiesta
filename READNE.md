# 无处不在的嘉年华 (Ubiquitous Fiesta)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)

Neo-arcade mini games collection. Every game is a self-contained HTML file engineered purely with HTML5 Canvas and vanilla JavaScript, zero third-party framework overhead. Perfect for quick pick-up-and-play sessions.

---

## 🎮 Games

### 🐍 Cyber Snake (赛博贪吃蛇) — `cyber-snake.html`

Classic snake with a cyberpunk twist: neon glow snake, progressive speed-up every 5 apples, and local high-score persistence.

- **Controls**: `W A S D` / arrow keys to steer, `Space` to pause.
- **Features**: local high score via `localStorage`, neon glow rendering, accelerating difficulty.

### 🧱 Cyber Breakout (赛博打砖块) — `cyber-breakout.html`

An interactive, ultra-responsive 2D arcade breakout game engine. Custom collision detection with bounding box intersection and momentum reflection, neon color-coded brick rows, and mouse-or-keyboard paddle control.

- **Controls**: mouse or `←` / `→` to move the paddle, `Space` to launch the ball.
- **Features**: angle-dependent paddle deflection, 6-row neon brick grid, 3 lives.

### 🧩 Cyber Tetris (赛博俄罗斯方块) — `cyber-tetris.html`

Classic falling-block stacking with neon tetrominoes, hold-to-speed soft drop, hard drop, next-piece preview, and level-based acceleration.

- **Controls**: `←` / `→` move, `↑` rotate, `↓` soft drop, `Space` hard drop, `P` pause.
- **Features**: 7 tetromino shapes, line-clear scoring, progressive speed.

### 🔢 Cyber 2048 (赛博数字合并) — `cyber-2048.html`

Slide and merge equal tiles to reach 2048. Neon color scale per tile value, local best score.

- **Controls**: arrow keys or `W A S D` to slide.
- **Features**: merge mechanics with score, win/lose detection, local high score.

### 🃏 Cyber Memory (赛博记忆翻牌) — `cyber-memory.html`

Flip neon symbol cards and match all 8 pairs in as few steps as possible.

- **Controls**: click cards to flip.
- **Features**: 4x4 grid, pair counting, step counting.

### ❎ Cyber Tic-Tac-Toe (赛博井字棋) — `cyber-ttt.html`

Tic-tac-toe against an unbeatable minimax AI. Pink X vs cyan O.

- **Controls**: click an empty cell to place your mark.
- **Features**: perfect-play AI, win/lose/draw scoreboard.

### 🔨 Cyber Whack (赛博打地鼠) — `cyber-whack.html`

Whack neon moles popping out of 9 holes within 30 seconds. Misses cost points.

- **Controls**: click a visible mole to score.
- **Features**: 30s countdown, miss penalty, fast-paced arcade action.

---

## 🎯 Key Highlights

- **⚡ Zero External Dependencies**: 100% pure native JavaScript, HTML5 Canvas, and modern CSS3.
- **🕹️ Precision Physics Engine**: Custom collision detection utilizing bounding box intersection and continuous momentum reflection.
- **🎨 Cyberpunk Aesthetic**: High-refresh glow bloom effects simulated directly within Canvas context shaders.
- **📱 Fluid Input Handling**: Native event listeners supporting smooth mouse tracking, low-latency keyboard controls, and responsive state pause.
- **📈 Progressive Difficulty Curve**: Real-time velocity scaling and dynamic grid re-generation across progressive levels.

---

## 🧱 Architecture Overview

```text
├── index.html            # Game lobby / entry page
├── cyber-snake.html      # Cyber Snake mini game (self-contained)
├── cyber-breakout.html   # Cyber Breakout mini game (self-contained)
├── cyber-tetris.html     # Cyber Tetris mini game (self-contained)
├── cyber-2048.html       # Cyber 2048 mini game (self-contained)
├── cyber-memory.html     # Cyber Memory mini game (self-contained)
├── cyber-ttt.html        # Cyber Tic-Tac-Toe mini game (self-contained)
├── cyber-whack.html      # Cyber Whack mini game (self-contained)
└── README.md             # Project documentation
```

## 🚀 Quick Start

```bash
git clone https://github.com/Hulaquan685-CMYK/ubiquitous-fiesta.git
cd ubiquitous-fiesta
# Simply double-click index.html or launch with Python:
python3 -m http.server 8080
```

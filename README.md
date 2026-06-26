# 🧱 Brick Breaker - MASM Assembly Game

## A Complete DOS Gaming Experience Built in x86 Assembly


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![MASM](https://img.shields.io/badge/MASM-6.11-blue)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Platform](https://img.shields.io/badge/Platform-DOSBox-orange)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Language](https://img.shields.io/badge/Language-Assembly-red)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Graphics](https://img.shields.io/badge/Graphics-VGA%20Mode%2013h-purple)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Status](https://img.shields.io/badge/Status-Complete-green)



---

# 📖 Overview

**Brick Breaker** is a classic arcade-style game developed entirely in **MASM x86 Assembly Language** as a semester project for the **Computer Organization and Assembly Language (COAL)** course. The game runs in **VGA Mode 13h (320×200, 256 colors)** and uses direct video memory access for pixel-perfect rendering.

The game features **3 progressive levels**, real-time ball physics, collision detection, score tracking, lives system, and collectible power-ups, delivering a complete retro arcade gaming experience.

---

# 🛠️ Tech Stack

- **Language:** MASM x86 Assembly
- **Assembler:** MASM 6.11
- **Platform:** DOSBox
- **Graphics:** VGA Mode 13h (320×200, 256 Colors)
- **Architecture:** Intel 8086 Real Mode

---

# 💊 Power-Up System

| Power-Up | Color | Effect | Duration |
|----------|-------|--------|----------|
| 🟦 Cyan | `03h` | Slow Ball | 500 Frames |
| 🟥 Red | `04h` | Fast Ball | 500 Frames |
| 🟩 Green | `02h` | +1 Extra Life | Instant |
| 🟨 Yellow | `0Eh` | Wide Paddle | 600 Frames |
| 🟪 Purple | `0Dh` | Narrow Paddle | 600 Frames |

### ✨ Features

- Random spawn every **3rd brick break**
- Falls toward the paddle for collection
- Only one bonus is active at a time
- Timer-based effect expiration

---

# 🚀 How to Run

## 📋 Prerequisites

- Visual Studio Code
- MASM/TASM Extension for Visual Studio Code

## ⚙️ Setup Guide

```text
   1. Install Visual Studio Code
        Download from: https://code.visualstudio.com/

   2. Install "MASM/TASM" extension in VS Code
        Go to Extensions (Ctrl+Shift+X) → Search "MASM/TASM" → Install

   3. Open the .asm file in VS Code

   4. Right-click → "Run ASM code"
        OR Press Ctrl+Shift+B to build

   5. The extension auto-assembles and launches DOSBox
```

---

# 🎮 How to Play

## Controls

| Key | Action |
|------|--------|
| `←` `→` or `A` `D` | Move Paddle |
| `SPACE` | Launch Ball |
| `ENTER` | Confirm / Select |
| `ESC` | Return / Exit |
| `↑` `↓` | Navigate Menu |
| `F2` | Skip to Level 2 (Debug) |

## Objective

- 🧱 Break all bricks to advance to the next level.
- 💊 Catch falling power-ups for special abilities.
- ❤️ Avoid losing the ball below the paddle.
- 🏆 Complete all 3 levels to win the game.

---

# 🎬 Demo Video

<div align="center">

[![Watch Demo Video](https://img.shields.io/badge/🎥%20Watch%20Gameplay%20Demo-Click%20Here-success?style=for-the-badge)](https://drive.google.com/file/d/1smroHxENNSQy9Ku7YpOGF-hYYwEIorSm/view?usp=drivesdk)

</div>

---
# 🎬 Documentation 

   For gameflow and detailed documentation check out the Brick_Bricker_Documentation.pdf added in the repo.

# 👥 Team Members

- Sawaira Fareed
- Ermish Tabassum
- Ahmad Tanveer
- Hanzala Ahsan

---

# 📄 License

This project was developed for academic purposes as part of the **Computer Organization and Assembly Language** course at **FAST-NUCES**.

© 2026 All rights reserved.

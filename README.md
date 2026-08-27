# 👹 Soul Snatcher

**A fast-paced 3-phase boss fight built entirely in a single HTML file.**

Face a relentless demon that chases you, fires bullet spreads, and rains fireballs when enraged. **Parry pink bullets to charge your Soul Energy, then unleash the screen-wide Soul Laser.**

🌍 Fully playable in **English & Tunisian Arabic**.

---

## 🎮 Features

* 👹 **3-Phase Boss Fight** — survive three increasingly dangerous phases.
* 🏃 **Dodge-Based Combat** — move constantly and react to incoming attacks.
* 💗 **Parry Mechanic** — parry pink bullets to build Soul Energy.
* ⚡ **Soul Laser** — charge your energy and unleash a powerful screen-wide attack.
* 🔥 **Enraged Phase** — survive devastating fireball attacks.
* 💥 **Bullet Spreads** — dodge different projectile patterns.
* 🌍 **Bilingual** — play in English or Tunisian Arabic.
* 💻 **PC Support** — play with WASD or Arrow Keys.
* 📱 **Mobile Support** — play using on-screen touch controls.
* 📄 **Single HTML File** — the entire game is contained in one file.
* 🌐 **Browser-Based** — no installation or complicated setup required.

---

## 🕹️ How to Play

Your goal is simple:

> **Survive the boss. Master the parry. Charge the Soul Laser.**

### 👹 Phase 1 — The Hunt

The demon begins chasing you while launching projectile attacks. Learn its patterns and stay mobile.

### ⚡ Phase 2 — The Assault

The fight gets faster and more aggressive. You'll need better movement and timing to survive.

### 🔥 Phase 3 — Enraged

The demon reaches its most dangerous state, combining aggressive bullet spreads with raining fireballs.

### 💗 Parry → Charge → Destroy

Pink bullets aren't just attacks — they're your opportunity.

**Parry them successfully to build Soul Energy.** Once you've charged enough energy, unleash the **Soul Laser** and strike back.

---

## 🎮 Controls

### 💻 PC

Use either **WASD** or the **Arrow Keys**:

| Action     | WASD | Arrow Keys |
| ---------- | ---- | ---------- |
| Move Up    | `W`  | `↑`        |
| Move Down  | `S`  | `↓`        |
| Move Left  | `A`  | `←`        |
| Move Right | `D`  | `→`        |

### 📱 Mobile

Use the **on-screen touch buttons** to move your character.

**No keyboard required.** 📱🎮

---

## 🌍 Languages

Soul Snatcher is fully playable in:

* 🇬🇧 **English**
* 🇹🇳 **Tunisian Arabic**

Switch between languages directly within the game.

---

## 🛠️ Technologies

The project uses a deliberately simple stack:

* `HTML5`
* `CSS`
* `JavaScript`
* `HTML Canvas`

### 📄 One File. Zero Dependencies.

Soul Snatcher doesn't require a framework, package manager, or build system.

```text
HTML
 ├── CSS
 ├── JavaScript
 └── Canvas
```

Everything runs directly in the browser.

---

## 🧠 The Core Gameplay Loop

```text
        👹 BOSS ATTACKS
              ↓
        🏃 DODGE ATTACKS
              ↓
         💗 PARRY BULLETS
              ↓
       ⚡ BUILD SOUL ENERGY
              ↓
        🔥 SOUL LASER
              ↓
       💥 DAMAGE THE BOSS
              ↓
       👹 NEXT PHASE
```

The further you progress, the more dangerous the fight becomes.

---

## 🎨 The Process

Soul Snatcher started with a simple idea: **build a complete boss fight inside a single HTML file.**

The first step was creating the core game loop, player movement, and boss behavior.

From there, the combat system was expanded with projectile attacks and collision detection. The boss was then divided into three phases, with each phase introducing more aggressive behavior.

The **parry system** became the main risk-and-reward mechanic. Instead of simply avoiding every attack, players can attempt to parry pink bullets and use successful parries to charge the Soul Laser.

After the core mechanics were working, additional attacks such as bullet spreads and fireballs were introduced to make the later phases progressively more challenging.

The final stages focused on polishing the experience with animations, visual effects, interface elements, mobile controls, and bilingual support.

The result is a complete browser-based boss fight contained inside **one HTML file**.

---

## 📚 What I Learned

Building Soul Snatcher provided hands-on experience with several areas of browser game development.

### 🎮 Game Loops

Managing a continuous game loop for:

* Player movement
* Boss movement
* Projectiles
* Collisions
* Attacks
* Animations
* Game states

### 💥 Collision Detection

Creating interactions between the player, boss, projectiles, parries, and the Soul Laser required handling collisions continuously during gameplay.

### 🧠 Game State Management

The boss changes behavior throughout the fight:

```text
Phase 1 → Phase 2 → Phase 3 → Victory / Defeat
```

Each phase has its own attack patterns and difficulty.

### 💗 Timing-Based Mechanics

The parry system relies on timing rather than simply holding a button. Players have to recognize incoming pink bullets and react at the right moment.

### 🎨 Canvas Rendering

HTML Canvas is used to render the game world, characters, projectiles, effects, and combat animations directly in the browser.

### 📱 Responsive Input

Supporting both keyboard and touchscreen controls required designing the gameplay around two different input methods without changing the core mechanics.

### 🌍 Localization

Adding English and Tunisian Arabic support introduced another challenge: keeping the interface and gameplay experience understandable across both languages.

---

## 🚀 Running the Project

Because Soul Snatcher is contained in a single HTML file, there is no installation process.

### 1. Clone the repository

```bash
git clone https://github.com/firasmallek/SOUL-SNATCHER---mini-game.git
```

### 2. Open the project

```text
cd SOUL-SNATCHER---mini-game
```

### 3. Launch the game

Open:

```text
index.html
```

in your browser.

**That's it. 🎮**

No `npm install`.
No build process.
No server required.

---

## 📁 Project Structure

```text
Soul-Snatcher/
└── index.html
```

**The entire game lives inside one file.**

---

## 🔮 Possible Improvements

Some ideas for future versions:

* 🎵 More music and sound effects
* 👹 Additional bosses
* ⚔️ More attack patterns
* 🏆 High-score system
* 💀 Difficulty modes
* 🎨 More visual effects
* 🎮 Additional control options
* 📱 Further mobile optimization
* 🏅 Achievements and challenges
* 🌎 Additional language support

---

## 👤 About

**Soul Snatcher** is a browser game project built to explore **JavaScript game development, Canvas rendering, combat systems, collision detection, animations, responsive controls, and localization**.

The project was intentionally kept inside a **single HTML file** to explore how far a complete playable game could be taken without frameworks or external dependencies.

---

## 🎥 Gameplay

https://github.com/user-attachments/assets/1480f6a4-8c85-420f-8e7f-e1df9be8838f

## ⭐ Support

If you enjoyed **Soul Snatcher**, consider giving the repository a ⭐ on GitHub!

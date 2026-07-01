# Circles_Tower_Defence
A tower defence game where all the towers and enemies are circles!

Fully-featured, browser-based tower defense game built with pure HTML5 Canvas and JavaScript. No dependencies, no build step—just open the file and play.

---

## 🎮 Overview

Defend your realm against waves of geometric invaders! Place towers, upgrade them, cast powerful spells, and survive through 5 unique themed levels. With 14 tower types, 6 enemy varieties, 4 difficulty modes, and an endless mode, Circles Tower Defence offers deep strategy and replayability—all in a single HTML file.

---

## ✨ Features

- **5 Themed Levels** — Classic, Sci-Fi, Biohazard, Warzone, and Nexus
- **14 Unique Towers** — From basic cannons to reality-tearing Void Rifts
- **6 Enemy Types** — Basic, Fast, Heavy, Armored, Flying, and Boss
- **4 Difficulty Modes** — Easy, Normal, Hard, and Insane
- **Tower Upgrades** — Upgrade any tower up to Level 3
- **Path Traps** — Place mines, acid pools, spike traps, and more directly on the enemy path
- **Level Spells** — Each level has a unique ultimate ability with a cooldown
- **7 Targeting Modes** — Furthest, Closest, Lowest HP, Highest HP, Fastest, Slowest, Boss
- **Speed Control** — Play at 1x, 2x, or 4x speed
- **Save/Load System** — Generate a save code to continue your run later
- **16 Achievements** — Unlock medals for completing challenges
- **Endless Mode** — Survive as long as possible after beating all 5 levels

---

## 🕹️ How to Play

1. **Start a New Game** — Choose your difficulty on the main menu.
2. **Place Towers** — Click a tower button, then click on the map to place it.
3. **Start the Wave** — Press **Start Wave** to begin spawning enemies.
4. **Upgrade & Sell** — Click a placed tower to upgrade it (max Level 3) or sell it for 60% of its total cost.
5. **Cast Spells** — Use your level's unique spell ability when things get tough.
6. **Survive** — Don't let enemies reach the end of the path! Lose all your lives and it's game over.

### Controls
| Key / Button | Action |
|-------------|--------|
| `Click` | Place tower / Select tower |
| `Space` | Pause / Resume |
| `⚡ Speed` | Toggle 1x / 2x / 4x |
| `🎯 Target` | Cycle targeting modes |
| `💾 Save` | Generate a save code |
| `🔄 Reset` | Restart the current run |

---

## 🏗️ Towers

| Tower | Cost | Damage | Range | Special |
|-------|------|--------|-------|---------|
| **Cannon** | 25 | 20 | 90 | Reliable splash damage |
| **Laser** | 45 | 12 | 130 | Fast fire rate, high accuracy |
| **Missile** | 70 | 35 | 110 | AoE explosion |
| **Sniper** | 120 | 80 | 200 | Extreme range & damage |
| **Poison** | 65 | 8 | 95 | Poison DoT cloud *(Unlock: Wave 10)* |
| **Freeze** | 90 | 5 | 100 | Slows enemies *(Unlock: Wave 20)* |
| **Plasma** | 150 | 60 | 120 | Pierces through enemies *(Unlock: Wave 30)* |
| **Electric** | 110 | 25 | 100 | Chain lightning *(Unlock: Wave 35)* |
| **PIAT** | 150 | 5000 | 125 | Armor-breaking AoE *(Unlock: Wave 15)* |
| **Mine** | 20 | 100 | — | Path trap, explodes on contact |
| **Acid Pool** | 15 | 75 | — | Path trap, poisons enemies |
| **Spike Trap** | 5 | 25 | — | Path trap, recharging spikes |
| **EMP Mine** | 10 | 50 | — | Path trap, stuns in AoE |
| **Void Rift** | 25 | 125 | — | Path trap, slows & damages |

&gt; **Path Traps** (Mine, Acid Pool, Spike Trap, EMP Mine, Void Rift) can only be placed **on** the enemy path, not next to it.

---

## 👾 Enemies

| Enemy | Health | Speed | Reward | Trait |
|-------|--------|-------|--------|-------|
| **Basic** | 1.0x | 1.0x | 1.0x | Standard grunt |
| **Fast** | 0.7x | 1.8x | 1.2x | Quick but fragile *(Wave 5+)* |
| **Heavy** | 2.5x | 0.6x | 1.8x | Tanky and slow *(Wave 10+)* |
| **Armored** | 2.0x | 0.8x | 2.0x | 50% damage reduction *(Wave 15+)* |
| **Flying** | 1.2x | 1.4x | 1.5x | Ignores path terrain *(Wave 20+)* |
| **Boss** | 8.0x | 0.4x | 2.5x | Massive health, appears every 15 waves |

---

## 🗺️ Levels

| Level | Theme | Available Towers | Spell |
|-------|-------|------------------|-------|
| 1 | 🏰 **Classic** | Cannon, Freeze, Sniper, Spike Trap | ⚡ **Boost** — 2x tower damage for 15s |
| 2 | 🤖 **Sci-Fi** | Electric, Laser, Plasma, EMP Mine | 🔋 **Overdrive** — 2x fire rate for 15s |
| 3 | ☣️ **Biohazard** | Poison, Plasma, Freeze, Acid Pool | ☣️ **Quarantine** — Halt spawn, poison all enemies |
| 4 | 💥 **Warzone** | Missile, Sniper, PIAT, Mine | ✈️ **Airstrike** — Massive damage to all enemies |
| 5 | 🌌 **Nexus** | **ALL** towers + Void Rift | ⛈️ **Cosmic Storm** — Random lightning strikes |

&gt; Towers are **cleared** at the start of each new level. Gold and lives carry over.

---

## ⚔️ Difficulty

| Mode | Start Gold | Lives | Enemy Speed | Enemy Health | Rewards | Spawn Delay |
|------|-----------|-------|-------------|--------------|---------|-------------|
| 🌱 **Easy** | 100 | 30 | 0.75x | 0.75x | 1.25x | 1.25x (slower) |
| ⚔️ **Normal** | 75 | 25 | 1.0x | 1.0x | 1.0x | 1.0x |
| 🔥 **Hard** | 50 | 20 | 1.25x | 1.25x | 0.75x | 0.75x (faster) |
| 💀 **Insane** | 25 | 15 | 1.5x | 1.5x | 0.5x | 0.5x (faster) |

---

## 🏆 Achievements

| Achievement | Description |
|-------------|-------------|
| 🩸 **First Blood** | Defeat your first enemy |
| 🏄 **Getting Started** | Reach wave 5 |
| 🌊 **Wave Warrior** | Reach wave 10 |
| 👑 **Wave Master** | Complete wave 15 |
| 🛡️ **Perfect Defense** | Complete a level without losing lives |
| ⬆️ **Maxed Out** | Upgrade a tower to level 3 |
| 🏗️ **Arsenal** | Place every tower type in one game |
| 🔥 **Hardcore** | Defeat the level 5 boss on Hard |
| 💀 **Madness** | Defeat the level 5 boss on Insane |
| 💰 **Mogul** | Accumulate 500 gold |
| 🏰 **Fortress** | Place 10 towers in one game |
| 💯 **Centurion** | Defeat 100 enemies total |
| ⚡ **Speed Demon** | Complete a wave at 4x speed |
| 👹 **Boss Slayer** | Defeat your first boss |
| ⚔️ **Standard Issue** | Defeat the level 5 boss on Normal |
| 🔋 **Light Show** | Place 3 laser towers at once |
| 🎯 **Pure Skill** | Complete a level without upgrading |
| ♾️ **Endless** | Reach wave 20 in Endless Mode |

&gt; Achievements are saved to your browser's `localStorage`.

---

## 💾 Save System

Your progress can be saved at any time during gameplay:

1. Click **💾 Save** in the control bar.
2. A save code will appear—**copy it**.
3. Later, click **📂 Load Game** from the main menu and paste your code.

Save codes encode your gold, lives, wave, level, towers, difficulty, and more.

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — Rendering
- **Vanilla JavaScript** — Game logic, no frameworks
- **CSS3** — UI styling and animations
- **localStorage** — Achievement persistence
- **Base64** — Save code serialization

---

## 📂 File Structure
```
circles-tower-defence/
└── index.html          # Everything is in here!
```

That's right—**the entire game is a single HTML file**. No build tools, no npm install, no bundlers. Just open it in any modern browser.

---

## 🚀 Running Locally

```bash
# Clone or download the file
git clone https://github.com/yourusername/circles-tower-defence.git

# Open in your browser
open circles-tower-defence/index.html
```
Or simply drag index.html into your browser window.

# ENJOY!!!

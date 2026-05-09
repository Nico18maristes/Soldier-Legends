[README.md](https://github.com/user-attachments/files/27558614/README.md)
# ⚔️ Soldiers Legends

> A fast-paced 2D multiplayer brawler — inspired by Brawl Stars, built from scratch in HTML5 Canvas.

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![Phase](https://img.shields.io/badge/phase-0%20%E2%9C%85%20%7C%201%20%F0%9F%94%A7-blue)
![Tech](https://img.shields.io/badge/tech-HTML5%20%2B%20Canvas%20%2B%20JS-orange)

---

## 🎮 What is this?

Soldiers Legends is a browser-based action game where two players battle it out in real time. Each character (called a **Brawler**) has unique abilities, a basic attack, and a powerful super move.

The long-term goal is **online multiplayer** — each player on their own device — with a full roster of 12+ brawlers, maps with obstacles, a progression system, and ranked play.

---

## ✅ Current State — Phase 0 (Prototype)

The base prototype is fully playable on a single device with a shared keyboard.

**What's already working:**
- 3 playable brawlers: **Troy**, **Ragnar** and **Trix**
- HP bars and super charge bars
- Basic attacks and unique ultimates per character
- Character selection screen before the match
- Impact particles and projectiles
- Local 2-player controls (shared keyboard)

---

## 🕹️ How to Play

Open `soldiers_legends_game.html` in any modern browser. No installation needed.

| | Player 1 | Player 2 |
|---|---|---|
| **Move** | `W A S D` | `↑ ↓ ← →` |
| **Basic Attack** | `F` | `L` |
| **Super / Ulti** | `G` | `;` |

---

## 🧬 Brawlers

| Name | Rarity | Type | Special |
|------|--------|------|---------|
| **Troy** | Master | Ranged | Lasso that pulls the enemy |
| **Ragnar** | Legend | Melee | Howl that attracts enemies |
| **Trix** | Rare | Ranged | Hack that blocks basic attacks |

More brawlers coming in Phase 4 (see roadmap below).

---

## 🗺️ Development Roadmap

| Phase | Description | Status |
|-------|-------------|--------|
| **0** | Base prototype (3 brawlers, local 2P) | ✅ Done |
| **1** | Smooth movement, visual states, damage numbers, screen shake | 🔧 In progress |
| **2** | Online multiplayer (Node.js + Socket.io, room codes, bots) | 📋 Planned |
| **3** | Maps with walls, bushes and tactical zones | 📋 Planned |
| **4** | Full brawler roster (12 characters) | 📋 Planned |
| **5** | Progression system (XP, levels, unlocks, currencies) | 📋 Planned |
| **6** | Full UI (menus, lobby, results screen, mobile controls) | 📋 Planned |
| **7** | Polish, sound, balance and ranked mode | 📋 Planned |

---

## 🛠️ Tech Stack

- **Game engine:** HTML5 Canvas + vanilla JavaScript (no frameworks)
- **Multiplayer (planned):** Node.js + Socket.io
- **Database (planned):** Firebase or Supabase
- **Hosting (planned):** Vercel / Railway + GitHub Pages

---

## 👥 Team — Grupo Troy

- **Nico** — [@Nico18maristes](https://github.com/Nico18maristes)
- Mario
- Pau

---

## 📜 Collaboration Rules

- Always write your name before your message in the chat: `Mario:`, `Pau:`, etc.
- Each phase has its own code file — don't mix phases.
- Announce what you're working on before you start.
- If something breaks, don't delete it — add a comment explaining the problem.
- Important decisions (changing a mechanic, removing something) are made as a team.

**Work order:** Make it work → Make it look good → Make it sound good → Make it balanced.

> A finished simple game is better than a thousand half-baked ideas.

# Neon Rift 2

**Neon Rift 2** is a fast-paced **HTML5 canvas action platformer** built entirely as a **single self-contained HTML file** — no assets, no libraries, no build step.

It expands on the original *Neon Rift Runner* with deeper combat mechanics, procedural level segments, minibosses, a full boss fight, and significantly improved game feel.

---

⚠️ **LICENSE & USAGE NOTICE — READ FIRST**

This repository is **source-available for private technical evaluation and testing only**.

- ❌ No commercial use  
- ❌ No production use  
- ❌ No academic, institutional, or government use  
- ❌ No research, benchmarking, or publication  
- ❌ No redistribution, sublicensing, or derivative works  
- ❌ No independent development based on this code  

All rights remain exclusively with the author.  
Use of this software constitutes acceptance of the terms defined in **LICENSE.txt**.

---

## Key Features

- ⚡ Responsive, high-skill movement (dash, wall slide, double jump)
- 🔫 Ranged combat, melee attacks, and projectile reflection
- 🧠 Enemy AI with distinct behaviors (patrollers, shooters, flyers)
- 🧬 Hybrid levels:
  - handcrafted intro
  - procedural mid-game
  - fixed miniboss + boss arenas
- 👾 Miniboss + multi-phase boss encounter
- 💥 Screen shake, hit-stop, particles, and impact feedback
- 🔊 Procedural sound effects via Web Audio API
- 📱 Touch controls for mobile
- 💾 Checkpoints and fair respawn system
- 📦 **One single HTML file**

---

## Controls

### Keyboard
| Action | Keys |
|------|------|
| Move | ← → / A D |
| Jump | ↑ / W / J |
| Dash | Shift / K |
| Shoot | Space |
| Melee | L |
| Pause | P |
| Restart | R |
| Mute Audio | M |

### Mobile / Touch
- Left side: movement
- Right side: jump / dash / shoot / melee buttons
- HUD icons appear automatically on small screens

---

## How to Play

1. Download or clone the repository
2. Open `Neon Rift 2.html` in any modern browser
3. Play instantly — works offline

No server, no install, no dependencies.

---

### Gameplay Overview

- Fight through increasingly difficult segments
- Activate checkpoints to save progress
- Defeat the miniboss to unlock the final arena
- Beat the boss to complete the run

Combat rewards:
- aggressive play
- dash timing
- melee reflection windows
- movement mastery

---

## Technical Overview

- **Rendering:** HTML5 `<canvas>`
- **Game loop:** `requestAnimationFrame`
- **Physics:** Custom AABB collision + resolution
- **Level generation:** Seeded procedural segments
- **Audio:** Synthesized SFX (Web Audio API)
- **Input:** Keyboard + unified touch system
- **Architecture:** Modular systems within a single file

No images. No audio files. No frameworks.

---

## Project Structure

Neon Rift 2.html

```yaml
Everything — HTML, CSS, JavaScript, rendering, physics, audio, and UI — is intentionally contained in one file.
```

---

## Why this exists

Neon Rift 2 is an experiment in:
- pushing **pure browser tech**
- maintaining **game feel without assets**
- designing real combat systems in minimal constraints

It’s meant to be:
- playable
- hackable
- and educational

---

## Ideas for Expansion

- Sprite art or shaders
- Additional biomes
- Enemy variants per segment
- Speedrun mode with timers
- Replay recording
- Controller support

---

## Contribution Policy

Feedback, bug reports, and suggestions are welcome.

You may submit:

- Issues
- Design feedback
- Pull requests for review

However:

- Contributions do not grant any license or ownership rights
- The author retains full discretion over acceptance and future use
- Contributors receive no rights to reuse, redistribute, or derive from this code

---

### License
This project is not open-source.

It is licensed under a private evaluation-only license.
See LICENSE.txt for full terms.

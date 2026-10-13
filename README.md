# 🌌 Piyush Gurjar — Living Pixel-Art Portfolio World

> *"Stories are the vessels through which we touch the infinite—whether carved through the lens of a camera, the silence of a stage, the precision of a smash on the court, or the quiet elegance of code."*
> — **Piyush Gurjar**

A production-quality, deeply atmospheric personal portfolio website engineered as a **tiny living pixel-art world**. Designed to celebrate Piyush's multidisciplinary identity as an **Actor, Filmmaker, Storyteller, Writer, Badminton Player, and Computer Science Student** (1st-year B.Tech CSE Core at JECRC University, Class of 2030).

---

## 🎮 Core Features & World Systems

### 1. 🌙 Living Pixel Canvas Night World (`canvas-world.js`)
- **Starfield & Celestial Sky**: 140+ twinkling stars with variable breathing phases and tints.
- **Radiant Pixel Moon**: Hand-rasterized moon with lunar crater textures and dual-layer bioluminescent corona glow.
- **Mountain & Grassland Silhouettes**: Layered parallax ridges bathed in deep starry midnight blues (`#060a17` to `#172554`).
- **Animated Pixel Oak Tree**: Swaying pixel foliage moving gently with the night breeze.
- **Peaceful Animal Silhouettes Under The Tree**:
  - 🐕 **Dog**: Gentle chest breathing, tail wagging, and ear twitches.
  - 🐈 **Cat**: Curled beside dog, rhythmic breathing, slow tail curl & swishes.
  - 🐦 **Sparrow**: Perched on the right branch with curious head tilts and tail rustles.
- **Floating Fireflies**: Drifting organic luminescent particles with pulsating alpha glow.
- **Natural Shooting Stars**: Streaking across the sky every 1–2 seconds with randomized angles, velocities, and particle tails.
- **Interactive Sky**: Click anywhere on the night sky to shoot an interactive meteor or trigger cosmic ripples!

### 2. ☄️ Meteor Navigation System (`meteor-nav.js`)
- Whenever any navigation link, hero button, or footer link is clicked:
  1. A diagonal pixel meteor hurtles rapidly down across the sky towards the exact interaction point.
  2. Upon arrival (~200ms), a crisp pixel explosion triggers with 38 multi-colored particle sparks and an expanding shockwave ring.
  3. Plays procedural synthesized launch whoosh and lowpass impact explosion audio.
  4. Smoothly transitions and scrolls to the selected section.

### 3. ⚡ Escalating Pokémon Companion System (`pokemon.js`)
Each section features a living, interactive pixel companion. **Only repeated clicks on that specific character advance its reaction sequence**:
- **Home — Pikachu**:
  - Idle: Ear twitch, tail bounce.
  - Click 1: *"Pika?"* (Curious head tilt)
  - Click 2: *"Piiii?!"* (Confused / annoyed spark)
  - Click 3: *"Pikaaa! PIKAAAAAA!!"* (Angry shaking with electric cheek sparks)
  - Click 4: *"..."* (Tense silence & glowing red eyes)
  - Click 5: ⚡ **THUNDER ATTACK!** (Screen-wide white flash, pixel lightning bolts across the sky, rumbling bass thunder, and cute puff of smoke exit!)
- **About — Bulbasaur**:
  - Idle: Plant bulb breathing.
  - Sequence: *"Bulba-saur!"* ➔ Vine Whip swat ➔ Leech Seed sprouting seedlings ➔ Golden Solar Beam charging ➔ 🌸 **SOLAR BEAM BURST** with floral petal cyclone exit!
- **Skills — Squirtle**:
  - Idle: Bouncing with cool pixel sunglasses.
  - Sequence: Sunglass gleam twinkle ➔ Bubble Beam spawning clickable/hoverable popping bubbles ➔ Withdraw shell spin ➔ Water torrent ➔ 🏄‍♂️ **HYDRO PUMP SURF** wave exit!
- **My World — Charmander**:
  - Idle: Tail flame crackling with real ember particles.
  - Sequence: *"Char-char!"* ➔ Dancing ember sparks ➔ Fire Spin vortex ➔ Deep flame inhale ➔ 🔥 **FLAMETHROWER** blaze dash exit!
- **Guestbook — Meowth**:
  - Idle: Forehead Koban amulet coin shimmer.
  - Sequence: *"Meowth, that's right!"* ➔ Fury Swipes claws slashes ➔ Pay Day golden coin shower ➔ Giovanni dream bubble ➔ 🚀 **TEAM ROCKET BLAST OFF** rocket exit!
- **Contact — Togepi**:
  - Idle: Snuggled inside its speckled egg, peeking over edge.
  - Sequence: *"Togepriii~"* peek-a-boo ➔ Metronome finger wag with rainbow sparkles ➔ Joyful bouncy dance ➔ Farewell chime ➔ 🦅 **PIDGEOT SWOOP RESCUE!** (Pidgeot swoops from high sky, scoops Togepi in its talons, and soars into the night sky!)

### 4. 🔊 8-Bit Web Audio API Synthesizer (`audio.js`)
- 100% procedurally synthesized retro chiptune audio (no broken external audio links or slow buffers).
- Sounds: Meteor launch whistle, impact boom, thunder crash, vine whip, solar beam charge, bubble pop, hydro pump sweep, ember crackle, flamethrower roar, Pay Day coin clink, scratch, rocket boost, metronome arpeggio, Pidgeot swoop/wing flap, heart like chime, level-up jingle.
- Strict user-gesture initialization and HUD [ON/OFF] toggle.

### 5. 📖 Skills: Active Passions vs Currently Loading
- **Things I Love / Actively Do**:
  - **Acting**: Method immersion, monologue delivery, vocal projection, stage presence.
  - **Badminton**: Attacking smash, court agility, reaction speed, mental tenacity.
  - **Writing**: Screenplays, character arcs, dialogue, poetic narratives.
- **Currently Loading / In Progress** (visualized with animated pixel loading bars, CPU/RAM counters, and zero fake senior claims):
  - **Video Editing**: [████████████░░░░] 68% (Pacing, cuts, Premiere / DaVinci workflows, sound sync, color grading).
  - **Coding**: [██████████░░░░░░] 54% (1st-Year B.Tech CSE Core fundamentals at JECRC University, C/C++, Python, data structures, web canvas).

### 6. 📜 The Living Guestbook (`guestbook.js`)
- *"Leave your thoughts, stories, or a little piece of yourself."*
- Avatar selector: ⭐ Star, 💖 Heart, 🪶 Feather, 🐶 Dog, 🐱 Cat, 🧪 Potion, 🎮 Gameboy, 🏸 Shuttlecock.
- Mood stamps: Dreamer, Inspired, Storyteller, Court Buddy.
- Genuine `localStorage` persistence, pre-seeded community notes, real-time message posting, and heart/like reactions.

### 7. 📬 Contact & Direct Signal
- **Email**: `piyushg152007@gmail.com` with 1-click clipboard copy & mailto.
- **Phone**: `9256803722` with 1-click clipboard copy & direct dial.
- **Campus Radar**: JECRC University, Jaipur (Class of 2030).
- Interactive dispatch terminal.

---

## 🚀 How to Run Locally

You can run this website immediately without needing Node.js or any build tools:

1. **Direct Open**: Double-click `index.html` in your file explorer, or open it in Microsoft Edge, Google Chrome, Brave, Firefox, or Safari:
   ```powershell
   Start-Process "C:\Users\Asus\.gemini\antigravity\scratch\piyush-gurjar-portfolio\index.html"
   ```

2. **Local Web Server (Optional)**:
   If you have Python or any HTTP server:
   ```powershell
   python -m http.server 8000
   ```
   Or with VS Code extension *Live Server*.

---

## 🌐 Instant Deployment Options

- **GitHub Pages**: Push this directory to a repository named `username.github.io` and enable GitHub Pages in repo settings.
- **Vercel / Netlify**: Drag-and-drop the project folder into Vercel or Netlify for instantaneous production URL with HTTPS!

# 🎲 Nairaland 3D Ludo Game Challenge

<p align="center">
  <img src="./images/game-screenshot.png" alt="Nairaland 3D Ludo Game" width="700">
</p>

<p align="center">
  <em>A fully playable, visually stunning 3D Ludo game built entirely in a single HTML file</em>
</p>

---

## 🌟 Overview

**3D Ludo** is a complete implementation of the classic board game, featuring beautiful 3D graphics and smooth animations. Built using **three.js** and delivered as a single HTML file for maximum portability and ease of use. 

Created for the **Nairaland Coding Challenge (December 2025)**, this project showcases modern web technologies without requiring any build tools or external dependencies beyond the three.js CDN.

---

## 🚀 Quick Start

### Playing the Game

1. **Download** the `index.html` file
2. **Open** it directly in any modern browser (Chrome, Firefox, or Edge recommended)
3. **Click** "Start Game" and select the number of players (2-4)
4. **Enjoy** the game! 

> **No installation required** – just open and play!

### Local Development Server (Recommended for Best Experience)

To avoid potential CORS issues and get faster loading:

```bash
# Navigate to the folder containing index.html
cd /path/to/your/game/folder

# Run a simple local server (requires Python)
python -m http.server 8080

# Then open your browser and go to:
# http://127.0.0.1:8080/
```

---

## ✨ Key Features

### 🎨 Stunning 3D Graphics

- **Circular game board** with vibrant colored quadrants
- **Animated tokens** with smooth hopping movements
- **Realistic dice rolling** with 3D spin effects
- **Cinematic camera movements** that follow the action (toggleable)
- **Visual markers** for nests, safe tiles, and lucky stars

### 🎮 Complete Ludo Gameplay

All traditional Ludo rules are faithfully implemented: 

- ✅ **Roll a 6** to move tokens out of home
- ✅ **Capture opponents** by landing on their tokens (except on safe tiles)
- ✅ **Safe tiles** at each colored starting position
- ✅ **Lucky stars** grant bonus rolls when landed on exactly
- ✅ **Home stretch** unlocks after completing the full board circuit (52 steps)
- ✅ **Exact roll required** to reach the center and finish
- ✅ **Extra turn** awarded for rolling a 6
- ✅ **2-4 players** support (Human vs AI opponents)

### 🤖 Intelligent AI Opponents

- **Smart decision-making**:  AI prioritizes capturing opponents
- **Strategic movement**: Falls back to advancing tokens when no captures available
- **Adaptive difficulty**: Provides competitive gameplay for all skill levels

### 🛠️ Player-Friendly Features

- **One-time undo** per move for mistake correction
- **Autosave system** using localStorage – resume anytime
- **Keyboard shortcuts** for faster gameplay
- **Glowing indicators** show which tokens can legally move
- **Toast notifications** for important game events
- **Rules modal** with comprehensive gameplay instructions
- **Dark/Light theme** toggle for visual preference
- **Responsive design** adapts to all screen sizes

---

## 🎯 How to Play

### Game Setup

1. Click **"Start Game"**
2. Select **number of players** (2-4) from the dropdown
3. You play as **Red** 🔴, AI controls other colors (Blue 🔵, Yellow 🟡, Green 🟢)

### Your Turn

1. **Click "Roll"** (or press `R`) to roll the dice
2. **Movable tokens will glow** – click one to move it
3. **Capture opponents** by landing on their tokens (sends them home!)
4. **Land on a lucky star** (⭐) for a bonus roll
5. **Roll a 6** to get an extra turn

### Winning

- Get **all 4 of your tokens** to the center hub before your opponents
- Must roll **exact number** needed to enter the center
- First player to finish wins! 🏆

---

## ⌨️ Controls

### Mouse Controls
- **Click** tokens to select and move them
- **Drag** anywhere to rotate the camera view
- **Scroll** to zoom in/out

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `R` | Roll the dice |
| `1` | Select first movable token |
| `2` | Select second movable token |
| `3` | Select third movable token |
| `4` | Select fourth movable token |

### UI Buttons
- 👥 **Players** – Select number of players
- 🎥 **Camera FX** – Toggle cinematic camera movements
- 🌓 **Theme** – Switch between dark/light mode
- ▶️ **Start Game** – Begin a new game
- 📖 **Rules** – View complete game rules

---

## 🔧 Technical Details

### Architecture Highlights

- **Single HTML file**: Entire game contained in one portable file
- **No build process**: Pure vanilla JavaScript with ES6 modules
- **CDN-based**: Uses three. js v0.160.0 from CDN (no local dependencies)
- **Performance optimized**:  Efficient geometry reuse and minimal object creation
- **Responsive canvas**:  Automatically adapts to screen dimensions

### Technologies Used

- **[three. js](https://threejs.org/)** – 3D graphics rendering
- **Vanilla JavaScript** – Game logic and interactivity
- **CSS3** – Modern styling with animations
- **LocalStorage API** – Game state persistence

### Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full support |
| Firefox | ✅ Full support |
| Edge    | ✅ Full support |
| Safari  | ⚠️ Mostly supported |

---

## 📸 Screenshots

### Main Gameplay
<p align="center">
  <img src="./images/gameplay. png" alt="Main gameplay view" width="600">
  <br>
  <em>The beautiful 3D board with tokens in play</em>
</p>

### Dice Rolling Animation
<p align="center">
  <img src="./images/dice-roll.gif" alt="Dice rolling animation" width="400">
  <br>
  <em>Realistic 3D dice with smooth rolling physics</em>
</p>

> **Note**: Replace placeholders with actual screenshots from your `C:/Users/hp/Pictures/debug/Nl_ludogamechallenge_project` folder

---

## 🙏 Acknowledgments

This game was developed with assistance from **Grok (xAI)** for planning, debugging, and optimization. All code is original and contained within a single file.

Special thanks to the **Nairaland community** for inspiring this project through the December 2025 Coding Challenge.  

---

## 📄 License

**Free and open** to use, modify, and share.   
Built with ❤️ Open for Collaboration and work hmoustapher@gmail.com**. 

---

## 🎮 Ready to Play? 

**[Download the game](./index.html)** and start playing now! 

No installation, no setup – just pure gaming fun! 🎉

---

<p align="center">
  <strong>Made for Nairaland Coding Challenge – December 2025</strong>
  <br>
  <em>Built by Hmoustapher</em>
</p>

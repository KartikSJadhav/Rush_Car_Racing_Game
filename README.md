# 🏎️ Rush Car Racing Game

<img width="681" height="360" alt="Car Racing Game - Play Free Online Dodge Traffic _ Claude - Google Chrome 2026-05-15 15-20-15" src="https://github.com/user-attachments/assets/9e261b72-b766-4814-ab7d-4027e7ee9e6e" />




A fast-paced and visually immersive **2D Car Racing Game** built using **HTML5 Canvas, CSS, and Vanilla JavaScript**.  
Dodge incoming traffic, survive longer, and beat your highest score in this neon-inspired arcade racing experience.

---

# 🎮 Game Features

- 🚗 Smooth Car Controls
- ⚡ Dynamic Speed Increase
- 💥 Collision & Explosion Effects
- ❤️ Life System
- 📈 Score & High Score Tracking
- 🌳 Animated Environment
- 📱 Mobile Touch Support
- 🎨 Modern Neon UI Design
- 🛣️ Endless Racing Gameplay

---

# 🧠 Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 Canvas | Game Rendering |
| CSS3 | Styling & Animations |
| JavaScript | Game Logic |
| Local Variables | State Management |

---

# 📂 Project Structure

```bash
Rush-Car-Racing-Game/
│
├── index.html
├── assets/
│   ├── cars/
│   ├── sounds/
│   └── background/
│
├── screenshots/
│   ├── gameplay.png
│   └── gameover.png
│
└── README.md
```

---

# 🚀 How To Play

## 🎯 Objective

Avoid crashing into traffic vehicles and survive as long as possible to achieve the highest score.

---

## ⌨️ Controls

| Key | Action |
|-----|--------|
| ← / A | Move Left |
| → / D | Move Right |
| Touch Swipe | Mobile Steering |

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/rush-car-racing-game.git
```

## 2️⃣ Open Project Folder

```bash
cd rush-car-racing-game
```

## 3️⃣ Run Game

Simply open:

```bash
index.html
```

in your browser.

---

# 🎨 Gameplay Highlights

- Neon-themed futuristic UI
- Procedurally generated traffic
- Smooth lane movement system
- Animated road effects
- Responsive gameplay loop

---

# 🏁 Game Mechanics

```javascript
// Speed increases gradually
if (score % 300 === 0) {
  speed = Math.min(speed + 0.4, 14);
}
```

```javascript
// Collision Detection
function checkCollision(px, py, cx, cy) {
  return Math.abs(px-cx) < 26 &&
         Math.abs(py-cy) < 52;
}
```

---

# 📸 Screenshots

## 🚘 Gameplay
- Endless road racing
- Dynamic traffic generation
- Live score tracking
Game Overview :
<img width="628" height="585" alt="Car Racing Game" src="https://github.com/user-attachments/assets/c9671e54-3035-4d18-abb6-17dd163cb71b" />




## 💥 Crash Screen
- Animated explosion effect
- Replay system
- Best score display
Game Overview :
<img width="655" height="584" alt="Crash Screen" src="https://github.com/user-attachments/assets/ba297634-a990-4f6d-959e-83fd741cdecd" />



---

# 🔥 Future Enhancements

- 🎵 Background Music
- 🏆 Leaderboard System
- 🚘 Multiple Cars Selection
- 🌙 Day/Night Mode
- 🌍 Multiplayer Racing
- 🧩 Power-Ups & Boosters
- 🔊 Sound Effects

---

# 🤝 Contributing

Contributions are welcome!

```bash
# Fork Repository
# Create Branch
git checkout -b feature-name

# Commit Changes
git commit -m "Added new feature"

# Push Branch
git push origin feature-name
```

---

# 📄 License

Licensed under the **MIT License**.

---

# 👨‍💻 Developer

**Kartik S Jadhav**

> Built with ❤️ using HTML5 Canvas & JavaScript.
> Built using Claude.

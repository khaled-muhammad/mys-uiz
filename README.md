# MysUiz 💫 — Interactive Mystery Puzzle Game

**MysUiz** is a fun, interactive mystery game built with React. It combines code-breaking, device motion interaction, and pattern recognition puzzles to challenge and delight users through an immersive experience.

> 🚀 Built with love, motion effects, and a sprinkle of mystery.

---

## 🌟 Features

- 🔤 **Code Puzzle 1**: Detect hidden characters through typed input with real-time feedback.
- 🧭 **Motion-Driven Element**: Use mouse movement or device orientation to move mystery indicators.
- 🔓 **Modal Secrets**: Unlock hidden modals as you solve parts of the game.
- 🔐 **Hex Puzzle (Puzzle 2)**: Input a hex-based pin to unlock the next level.
- 💖 **Heart Connect Puzzle (Puzzle 3)**: Connect stars in the correct order to draw a heart.
- 🎉 **Completion Celebration**: Animated wave and congratulatory modal with final code reveal.

---

## 🎮 Gameplay Flow

1. **Start with Secret Code (KVM)** — Type `K`, then `V`, then `M` to unlock the first modal.
2. **Modal Reveals Code Puzzle 2** — A numeric/hex keypad to enter `4B 56 4D`.
3. **Animated Transition** — Unlock Puzzle 3 with beautiful wave animation.
4. **Connect the Heart** — Click stars in the correct order to draw a heart.
5. **Final Reveal** — Get your final success code: `URSA`.

---

## 🛠️ Tech Stack

- **React** (Functional Components + Hooks)
- **Tailwind CSS** for rapid, responsive, and beautiful design
- **Lucide Icons** for expressive visuals
- **Custom Motion Logic** using:
  - Mouse movement tracking
  - Device orientation (mobile gyroscope)
- **SVG animations** for dynamic UI
- **Modular Component Design**: Includes `Modal`, `useModal`, etc.

---

## 📁 Project Structure (Important Files)

```

├── App.jsx                # Main logic and game flow
├── Modal.jsx             # Custom modal component
├── useModal.js           # Custom hook for modal state
├── M.svg                 # Secret image/logo
├── index.css             # Tailwind + custom styles
└── ...

```

---

## 🔧 Setup & Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mysuiz.git
   cd mysuiz
```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Navigate to**

   ```
   http://localhost:5173/
   ```

---

## 📦 Build for Production

```bash
npm run build
```

Then deploy from the `dist/` folder to your favorite static hosting service (e.g., Vercel, Netlify).

---

## 📱 Mobile Friendly

MysUiz detects whether you're on mobile and adjusts both:

* Sensor input (tilt vs. cursor)
* UI element sizing

---

## 🧠 Final Code Rewards

* Puzzle 1: `KVM`
* Puzzle 2: `4B 56 4D`
* Puzzle 3: `URSA` ⭐

---

## 🧚 Designed For

This project is designed to entertain and engage friends or loved ones with personalized secret puzzles. Perfect for:

* Anniversaries
* Special surprises
* Fun educational challenges
* Mobile web games

---

## 💌 Credits

Made with ❤️ by [Your Name or Team Name]

Icons by [Lucide](https://lucide.dev/), Fonts by Google Fonts.

---

## 📜 License

MIT License. Free to use and modify for personal or educational purposes.
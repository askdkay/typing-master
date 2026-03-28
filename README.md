# ⌨️ Typing Master

A modern, sleek, and minimalist typing speed benchmark tool. Built entirely with pure HTML, CSS, and Vanilla JavaScript—no external frameworks required. This project is designed to provide a smooth, distraction-free typing experience.

## ✨ Key Features

* **Zen Mode (Focus Mode):** The moment you start typing, the rest of the UI (header, controls, footer) smoothly fades out and the screen locks scrolling, ensuring your absolute focus remains on the keyboard.
* **Live Analytics:** Real-time tracking of Raw WPM, Net WPM, Accuracy, and Time remaining.
* **Comprehensive Results Modal:** Upon completing a test, a sleek popup modal appears displaying your detailed performance metrics alongside a visual bar chart of your WPM history over time.
* **Dynamic Modes & Difficulty:** Choose between 'Words' or 'Quotes', and set your preferred difficulty to 'Easy', 'Hard', or 'Code' (featuring real programming syntax for developers!).
* **Local Storage History:** Your past test results and Personal Bests are automatically saved in your browser, providing a mini personal leaderboard.
* **Pro Keyboard Shortcuts:**
  * `Tab` - Quick restart (replays the same test)
  * `Esc` - Reset test (generates new words)
  * `Ctrl` + `Backspace` - Instantly delete the entire current word

## 🚀 How to Run

This is strictly a single-page application (SPA). There is no build step, `npm install`, or server setup required.

1. Clone this repository or download the `typing-master.html` file directly.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Brave, Safari).
3. Click anywhere on the screen or just start typing to begin the test!

## 🛠️ Tech Stack

* **HTML5:** Clean, semantic structure.
* **CSS3:** Custom variables, CSS Grid/Flexbox, smooth transitions, glassmorphism effects, and a subtle cyberpunk/phosphor teal aesthetic.
* **JavaScript (Vanilla):** DOM manipulation, accurate math formulas for WPM, interval-based timer logic, and native `localStorage` handling.

---
*Built with focus, speed, and clean code.*

# 🕹️ JavaScript Mini-Game Suite
> A collection of interactive web applications built to master Vanilla JavaScript, DOM Manipulation, and Logic.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

This repository serves as a portfolio of my early journey into frontend development. It features three distinct games, each focusing on different core programming concepts.

---

## 🎮 Games Included

### 1. 🎲 Dice Game

A multiplayer interactive game where users can compete by rolling dice.

* **Core Concepts:** Random number generation (`Math.random`), asynchronous functions (`setTimeout`), and dynamic image attribute modification.
* **Key Feature:** Ability to customize player names via prompts and update the DOM in real-time.

### 2. 🔮 Lucky Number

A logic-based guessing game that challenges the user to find a hidden number.

* **Core Concepts:** User input validation (`isNaN`, `parseInt`), conditional branching (`if/else`), and state management.
* **Key Feature:** Multi-layered validation to ensure the user enters a valid number within the specified range.

### 3. 🖼️ Picture Quiz

A visual quiz application that dynamically renders animal images and tracks scores.

* **Core Concepts:** Object-oriented programming (prototypes), array mapping, and complex DOM updates.
* **Key Feature:** Modular quiz engine that can be easily scaled with new questions and images.

---

## 🛠️ Technical Stack

* **HTML5:** Semantic structure for game interfaces.
* **CSS3:** Custom styling and responsive layouts.
* **JavaScript (ES6):** DOM API, event listeners, and game logic.

## 📂 Project Structure

```text
JS-Game-Suite/
├── index.html           # Main menu (portal)
├── dice-game/           # Dice game files
├── lucky-number/        # Guessing game files
└── picture-quiz/        # Quiz application files
```

## 🚀 How to Run

No build tools or dependencies are required. Since this is a static, client-side project:

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/JS-Game-Suite.git
   cd JS-Game-Suite
   ```
2. Open `index.html` directly in your browser, or serve the folder locally (recommended, since some browsers restrict certain JS features on `file://` pages):
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000` and navigate to each game from the main menu.

## 👤 Author

**Mohammed Nabeel**
Master's Student | University of Limerick

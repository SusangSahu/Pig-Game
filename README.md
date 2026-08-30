# 🎲 Pig Game

A fast-paced, two-player dice game built with Vanilla JavaScript, HTML5, and CSS3. Test your luck, but don't be too greedy—roll a 1 and you lose all your current points! The first player to reach 100 points wins the game.

## 🎮 How to Play (Rules)

1. **Roll the Dice:** The active player rolls the dice as many times as they want. Each roll adds to their *Current* score.
2. **The "Pig" (Rolling a 1):** If the active player rolls a `1`, their *Current* score resets to `0`, and their turn ends immediately.
3. **Hold:** At any time during their turn, the active player can click **Hold**. This adds their *Current* score to their *Total* score, securing those points, and ends their turn.
4. **Winning:** The first player to reach a *Total* score of 100 or more wins the game.

## ✨ Features

* **Interactive DOM Manipulation:** Seamless UI updates for dice rolls, score tracking, and active player switching.
* **State Management:** Tracks internal application state (active player, playing status, accumulated scores) using Vanilla JavaScript.
* **Modern UI/UX:** 
  * Glassmorphism design elements (backdrop filters, translucent backgrounds).
  * Smooth CSS transitions for active state changes.
  * Responsive and clean typography using the Nunito font family.
* **Game Reset:** Instantly start a new game at any point with the "New game" button.

## 🚀 Tech Stack

* **Frontend:** HTML5
* **Styling:** CSS3 (Flexbox, Linear Gradients, Absolute Positioning)
* **Logic:** Vanilla JavaScript (ES6+)

## 🛠️ Installation & Setup

Since this is a client-side only application, no build tools or package managers are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/pig-game.git](https://github.com/your-username/pig-game.git)

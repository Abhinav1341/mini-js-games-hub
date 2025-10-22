# 🎮 Mini JS Games Hub

A fun collection of mini JavaScript games built using **HTML**, **CSS**, and **JavaScript**!  
Perfect for beginners who want to learn web development, play simple games, and contribute new ideas 🚀

---

## 🕹️ About
This project is an open-source **games hub** where each mini-game is stored in its own folder.  
Every game runs directly in the browser and is written in pure HTML, CSS, and JS — no frameworks, no build tools, just fun and learning!

You can:
- Play simple web-based games 🎯  
- Learn JavaScript by reading the source code 💡  
- Add your own games and share them with the community 🌍  

---

## 📂 Project Structure
```
mini-js-games-hub/
│
├── index.html          # Home page listing all games
├── style.css           # Global styling
├── script.js           # Handles navigation and game loading
│
└── games/
    ├── tictactoe/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── snake/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── memory/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── whack-a-mole/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── reaction-timer/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── flappy-bird/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── breakout/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── pong/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── tetris/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── 2048/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── rock-paper-scissors/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── typing-test/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── simon-says/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── catch-the-dot/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── balloon-pop/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── kong-fights/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── catch-the-ball/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    ├── space-shooter/
    │   ├── index.html
    │   ├── style.css
    │   └── script.js
    └── 15-puzzle/
        ├── index.html
        ├── style.css
        └── script.js
```

---
## 🎮 Games Included

This repository currently features **58 interactive mini-games** built with HTML, CSS, and JavaScript:

### Puzzle Games
- **15 Puzzle** - Classic sliding tile puzzle to arrange numbers in order
- **2048** - Merge tiles to reach 2048
- **Color Squid Puzzle** - Color-based puzzle challenge
- **Logic Chain** - Solve logical sequences
- **Maiolike Block Puzzle** - Arrange blocks in patterns
- **Sudoku** - Fill the grid with numbers 1-9
- **Word Scramble** - Unscramble the letters to form words
- **Words of Wonders** - Word puzzle game

### Arcade Games
- **Asteroids** - Classic space shooter game
- **Breakout** - Break bricks with a bouncing ball
- **Flappy Bird** - Navigate through pipes by tapping
- **Frogger** - Help the frog cross the road
- **Pong** - Classic two-paddle arcade game
- **Snake** - Eat food and grow longer without hitting walls
- **Space Shooter** - Shoot down enemies in space
- **Tetris** - Stack falling blocks to clear lines
- **Whack-a-Mole** - Hit the moles as they pop up

### Action & Reflexes
- **Balloon Pop** - Pop balloons as fast as you can
- **Boom** - Explosive action game
- **Catch the Ball** - Catch falling balls
- **Catch The Dot** - Click the moving dot quickly
- **Endless Runner** - Run infinitely avoiding obstacles
- **Grass Defense** - Defend your territory
- **Island Survival** - Survive on a deserted island
- **Reaction Timer** - Test your reaction speed
- **Shadow Catcher** - Catch the moving shadows
- **Tap Reveal** - Tap to reveal hidden items
- **Tap the Bubble** - Pop bubbles by tapping
- **The Godzilla Fights** - Epic monster battle game
- **Tower Defense** - Defend against waves of enemies
- **World's Easiest Game** - Deceptively challenging game

### Strategy & Logic
- **8 Ball Pool** - Play pool/billiards
- **Connect Four** - Four-in-a-row strategy game
- **Rock Paper Scissors** - Classic hand game
- **Tic Tac Toe** - Classic X's and O's game

### Memory & Pattern Games
- **Color Clicker** - Click matching colors
- **Color Guessing Game** - Guess the RGB color value
- **Memory** - Match pairs of cards
- **Odd One Out** - Find the different item
- **Simon Says Game** - Repeat the pattern sequence
- **SimonSays** - Follow the pattern game

### Creative & Building
- **Burger Builder** - Create custom burgers
- **Cozy Blocks** - Build with cozy blocks
- **Meme Generator** - Create funny memes
- **Pixel Art Creator** - Draw pixel art creations

### Word & Trivia
- **Hangman** - Guess the word letter by letter
- **Quiz Game** - Answer trivia questions
- **Typing Test** - Measure your typing speed and accuracy

### Casual & Fun
- **Coin Toss Simulator** - Flip a virtual coin
- **Find Hidden Object** - Locate hidden objects in scenes
- **Line Game** - Draw lines without crossing
- **Link Game** - Connect matching items
- **Merge Lab** - Merge similar items together
- **Number Guessing Game** - Guess the secret number
- **Peglinko** - Drop the ball through pegs
- **Quote** - Display random inspirational quotes
- **Tileman** - Tile-based adventure
- **Tiny Fishing** - Relax with simple fishing

---

**Total: 58 Games and Growing!** 🎮

Each game is self-contained with its own HTML, CSS, and JavaScript files, making it easy to play, modify, or learn from.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ritaban06/mini-js-games-hub.git
cd mini-js-games-hub
```

### 2. Run locally
Simply open `index.html` in your browser — no setup needed!

### 3. How it works
The hub lists game cards from the `games` array in `script.js`. Each game entry includes:
- `name`: The display name of your game
- `path`: The relative path to your game's index.html file

---

## 💻 Tech Stack
- HTML5  
- CSS3  
- Vanilla JavaScript  

---

## 🤝 Contributing
We love contributions! ❤️  
To add your own game or fix an issue, please check the [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed steps.

---

## ✨ Contributors

#### Thanks to all the wonderful contributors 💖

<a href="https://github.com/ritaban06/mini-js-games-hub/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ritaban06/mini-js-games-hub" />
</a>

#### See full list of contributor contribution [Contribution Graph](https://github.com/ritaban06/mini-js-games-hub/graphs/contributors)  

---

## 🪪 License
This project is licensed under the [**MIT License**](LICENSE) — free to use and modify.  

---

## 🌟 Show Your Support
If you like this project, give it a ⭐ on GitHub and share it with your friends!  
Let’s make learning web development fun together! 🕹️

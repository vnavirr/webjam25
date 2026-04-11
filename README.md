# 🎨 Memory Color Matching

## 🎮 How to Play

1. When the game loads, all 12 cards briefly reveal their colors — memorize them!
2. Click any face-down card to flip it over
3. Click a second card to try to find its match
4. If the two cards share the same color, they stay face-up and are marked as matched
5. If they don't match, both cards flip back over after a short pause
6. Match all 6 pairs to win and see your final move count and time

## ✨ Features
* Peek phase — all cards are revealed for 3.5 seconds at the start of each game so you can study the layout
* Move counter — tracks every pair attempt you make
* Live timer — starts on your first click and stops when you win
* Toast notifications — instant feedback on matches and mismatches
* Win screen — animated confetti with your final moves and time displayed
* New Game button — restart at any time without refreshing the page
* Keyboard accessible — all cards are focusable and operable with Enter or Space
* Responsive layout — scales down cleanly on mobile screens

## 🛠️ Tech Stack

| Layer       | Technology                                                           |
| ----------- | -------------------------------------------------------------------- |
| Structure   | HTML5                                                                |
| Styling     | CSS3 (custom properties, grid, 3D transforms, keyframe animations)   |
| Logic       | Vanilla JavaScript (ES6+)                                            |
| Fonts       | Syne + DM Sans via Google Fonts                                      |
| Server      | serve (static file server)                                           |


## 🚀 Getting Started
**Prerequisites**
* Node.js v14 or higher
* npm (included with Node.js)

**Installation**
```
# Clone the repository
git clone https://github.com/your-username/memory-color-matching.git

# Navigate into the project folder
cd memory-color-matching

# Install the static file server
npm install
```

**Running the Game**
```
npm run serve
```
Then open your browser and go to http://localhost:3000.

**Dev Container (Optional)**
This project includes a `.devcontainer/devcontainer.json` configuration for use with VS Code Dev Containers. Opening the project in a dev container will automatically set up a Node.js 20 environment matching the original development setup.
Requirements: Docker Desktop and the Dev Containers extension for VS Code.

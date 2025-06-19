# Minesweeper Game - README

![Minesweeper Screenshot](https://via.placeholder.com/600x400?text=Minesweeper+Game+Screenshot)

## Table of Contents
- [Game Description](#game-description)
- [Current Features](#current-features)
- [Upcoming Features](#upcoming-features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Development Roadmap](#development-roadmap)

## Game Description
A classic Minesweeper game built with React.js and Tailwind CSS. The current version features a beginner-level 8x8 grid with 8 mines.

## Current Features
- Beginner level (8x8 grid with 8 mines)
- Timer to track game duration
- Mine counter showing remaining flags
- Left-click to reveal cells
- Right-click to place/remove flags
- Win/lose detection and display
- Responsive design for different screen sizes
- "New Game" button to restart at any time

## Upcoming Features

### Game Levels
- **Beginner**: 8x8 grid with 8 mines (current)
- **Intermediate**: 16x16 grid with 40 mines
- **Expert**: 30x16 grid with 99 mines

### User System
- User registration/login
- Personalized username display
- Game statistics tracking (wins, losses, best times)

### Scoreboard System
- Top scores for each difficulty level
- Personal best times tracking
- Scoreboard filtering (all-time, monthly, weekly)
- Score persistence using localStorage or a backend service

### Additional Features
- Custom game settings (adjustable grid size and mine count)
- Sound effects and toggle option
- Dark/light mode toggle
- Mobile-optimized controls
- Tutorial mode for beginners

## Installation
To run the game locally:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/minesweeper.git
```

2. Open `index.html` in your browser (no server required)

## How to Play
1. Left-click on a cell to reveal it
2. Right-click to place a flag where you think a mine is
3. Numbers show how many mines are adjacent to that cell
4. Clear all non-mine cells to win
5. Clicking on a mine ends the game

## Development Roadmap
1. [x] Implement basic game mechanics
2. [ ] Add intermediate and expert levels
3. [ ] Implement user authentication system
4. [ ] Build scoreboard functionality
5. [ ] Add sound effects and visual customization
6. [ ] Deploy to web hosting service


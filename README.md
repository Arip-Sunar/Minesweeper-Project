# Minesweeper

A classic Minesweeper game built to demonstrate programming fundamentals, game logic, and user interaction. The objective is to reveal all safe cells while avoiding hidden mines.

## Features

- 🎮 Classic Minesweeper gameplay
- 💣 Random mine placement
- 🔢 Automatic calculation of adjacent mine counts
- 🚩 Flag and unflag suspected mines
- 🌊 Auto-reveal empty neighboring cells
- 🏆 Win and game-over detection
- 📊 Multiple difficulty levels (optional)

## How to Play

1. Start the game.
2. Click on a cell to reveal it.
3. If the cell contains a mine, the game ends.
4. Numbers indicate how many mines are adjacent to that cell.
5. Right-click (or use the flag option) to mark suspected mines.
6. Reveal all non-mine cells to win the game.

## Project Structure

```
Minesweeper/
│── src/
│   ├── main.*
│   ├── game.*
│   ├── board.*
│   └── cell.*
│── assets/
│── screenshots/
│── README.md
└── LICENSE
```

## Game Logic

- A game board is generated with a fixed number of mines.
- Mines are placed randomly across the board.
- Each non-mine cell stores the number of adjacent mines.
- Revealing an empty cell automatically reveals neighboring empty cells.
- The game ends when:
  - A mine is revealed (Loss)
  - All safe cells are revealed (Win)

## Technologies Used

- Programming Language: *(Add your language here)*
- Framework/Library: *(e.g., JavaFX, Tkinter, Pygame, HTML/CSS/JavaScript, Swing)*

## Installation

1. Clone the repository.

```bash
git clone https://github.com/Arip-Sunar/minesweeper.git
```

2. Navigate to the project directory.

```bash
cd minesweeper
```

3. Run the application according to your programming language.

Example:

```bash
python main.py
```

or

```bash
npm install
npm start
```

## Future Improvements

- Timer
- Leaderboard
- Hint system
- First-click safety
- Dark mode
- Sound effects
- Responsive UI
- Save and load game

## Screenshots

Add screenshots of your game here.

## Learning Outcomes

This project demonstrates:

- Object-Oriented Programming
- Arrays and Matrices
- Recursion (DFS/BFS)
- Event Handling
- Random Number Generation
- Game State Management
- User Interface Design

## Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License.

## Author

**Arip Sunar**

GitHub: (https://github.com/Arip-Sunar)

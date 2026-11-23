# Tic Tac Toe

A simple two-player Tic Tac Toe game built with HTML, CSS, and vanilla JavaScript.

## Features

- Two-player game (O goes first, then X)
- Automatic winner detection across all 8 winning patterns
- Winner message with a **New Game** button
- **Reset** button to restart at any time
- Boxes are disabled after being clicked, and the whole board is locked once someone wins
- Responsive layout using `vmin` units

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)

## Project Structure

```
├── tictactoe.html   # Game markup
├── style.css        # Styling
└── script.js        # Game logic
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open the project folder.
3. Open `tictactoe.html` in your browser.

No installation or build step is needed.

## How to Play

1. Player **O** starts by clicking any empty box.
2. Players take turns placing **X** and **O**.
3. The first player to get three in a row (horizontally, vertically, or diagonally) wins.
4. Click **NEW GAME** or **Reset Button** to play again.

## Future Improvements

- Add draw/tie detection
- Show whose turn it is
- Add a score counter
- Add single-player mode against the computer

## Author

Your Name – [GitHub](https://github.com/sarthakgoyal16)

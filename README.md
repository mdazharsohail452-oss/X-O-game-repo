# X-O-game-repo
X-O Game (Tic Tac Toe)
A simple, interactive X-O (Tic Tac Toe) game built using HTML, CSS, and JavaScript. The game allows two players to take turns marking spaces in a 3×3 grid, with the goal of placing three marks in a row, column, or diagonal.

Features
Responsive and clean UI using HTML and CSS.

Two-player mode (Player X and Player O).

Real-time turn detection and move validation.

Automatic winner detection or draw declaration.

Restart button to reset the game board instantly.

Smooth animations and color transitions for better UX.

Technologies Used
HTML for structure

CSS for styling and responsiveness

JavaScript (ES6) for game logic and interactivity

How to Run
Clone or download the project folder.

Open the folder in any code editor.

Launch the index.html file in a web browser.

Play by clicking on empty boxes to place your symbol.

Project Structure
text
X-O-Game/
│
├── index.html       # Main HTML file
├── style.css        # Game board styling
└── app.js        # Game logic

Game Logic Overview
The board is represented by a 2D array or list of 9 cells.
The current player alternates after each valid click.
Winning combinations are checked after every move.
when any winning pattern mathes it will end game and disply winner(X or O).
start new game by clicking new game button. 

# Gamedev
Simple Chess Engine (HTML/CSS/JS)

This is a browser-based Chess Game built using pure HTML, CSS, and JavaScript, featuring:

⦁	Click-based movement
⦁	Valid move rules for all pieces
⦁	Check & checkmate detection
⦁	A simple Minimax AI (depth 2) for Black
⦁	Scoreboard with persistent match tracking
⦁	Clean chessboard UI

It requires no external libraries and runs entirely in the browser.

Features
Player vs AI

⦁	White is controlled by the player.
⦁	Black is played by a simple Minimax-based AI.

Piece Movement Rules

Supports valid movement for:

⦁	Pawn
⦁	Rook
⦁	Knight
⦁	Bishop
⦁	Queen
⦁	King

Includes:

⦁	Pawn double move
⦁	Pawn diagonal capture
⦁	Basic check detection

Game Logic:

⦁	Check & Checkmate alerts
⦁	Game resets after checkmate
⦁	Scoreboard updates after each win
⦁	Reset button to clear scores

AI Engine:

⦁	Uses a basic Game Tree and Minimax evaluation

How to Play:

⦁	Download/Clone the repository
⦁	Open index.html in any browser
⦁	Click a white piece → click a valid destination square
⦁	After your move, AI will play automatically
⦁	Game ends when either side checkmates

AI Evaluation Scores:

Piece	White	Black
Pawn	+1	-1
Knight	+3	-3
Bishop	+3	-3
Rook	+5	-5
Queen	+9	-9
King	+900	-900

Piece score evaluation (material-based)

AI plays defensively (minimizing score)

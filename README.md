🎮 Tic Tac Toe Game in Java

This project is a console-based 3×3 Tic Tac Toe game developed using Java. It allows two players to play the classic Tic Tac Toe game by taking turns and entering slot numbers through the terminal.

📌 Features

Two-player game (Player X and Player O)

Interactive console input

Automatic turn switching

Winner detection (rows, columns, diagonals)

Draw detection

Input validation (prevents invalid and duplicate moves)

Clean board display after every move

🛠️ Technologies Used

Java

Scanner class for user input

Arrays for board management

Exception handling for invalid inputs

▶️ How the Game Works

The game starts with an empty 3×3 board numbered from 1 to 9.

Player X plays first.

Players enter a slot number (1–9) to place their mark.

The program checks after each move:

If X or O has won

If the game is a draw

The game ends when a winner is found or all slots are filled.

🧩 Sample Board Layout
|---|---|---|
| 1 | 2 | 3 |
|-----------|
| 4 | 5 | 6 |
|-----------|
| 7 | 8 | 9 |
|---|---|---|

🏆 Winning Conditions

A player wins if they place three identical symbols (X or O) in:

Any row

Any column

Any diagonal

# What is Tic-Tac-Toe?
TicTacToe is a 2 player game played on a 3 x 3 board.
Each player is allotted a symbol (one X and one O).
Initially, the board is empty. 
Alternatively, each player takes a turn and puts their symbol at any empty slot. 
The first player to get their symbol over a complete row OR a complete column OR a diagonal wins.
---
## Qestion to Ask
- Will the game be played amongst only 2 players or can there be any number of players in future?
- Is the board size restricted to 3x3 or can it be any NxN?
- Can there be different ways to win?
- Can one of the players be a bot?
- Feature Suggestions:

  - Do we want to time a move? Skip/ Declare the other person as winner if the move doesn’t happen within x seconds.
  - Do we want to support undo operation?
  - Can there be some players who are just watching? Not playing.
  - Do we want to store analytics? Basically previous games, who played what move etc.
  - Support for tournaments? Basically a set of matches, each match between 2 players of the tournament.
---
## Expectations
- The code should be working and functionally correct
- Good software design practices should be followed:
- Code should be modular, readable, extensible
- Separation of concern should be addressed
- Project structured well across multiple files/ packages
- Write unit tests
- No need of GUI
---
## Problem Requirements
- Board can be of any NxN size.
- There can be two players.
- Each player will be allotted a symbol.
- The symbol can be one of O and X.
- The players can be either humans or bots.
- Each human player will have a name, email and profile image.
- Each bot player will have a difficulty level.
- Any random player can start the game.
- Then the players will take turns alternatively.
- The player with any consecutive N symbols in a row, column or diagonal wins.
- If the board is full and no player has won, the game is a draw.
---
## Entities and their attributes
- Game
  - Board
  - Players
- Board
  - Cells
- Cell
  - Row
  - Column
  - Symbol
- Human Player
  - Name
  - Email
  - Profile Image
- Bot Player
  - Difficulty Level
---

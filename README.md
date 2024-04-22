# connect-four

Build a connect-four game for the terminal, that supports two local players.

The game should support two players (X, O) until there is one winner. Connect four is a type of m-n-k game. An m,n,k-game is an abstract board game in which two players take turns in placing a stone of their color on an m-by-n board, the winner being the player who first gets k stones of their own color in a row, horizontally, vertically, or diagonally.

## Features

- Play abstract m-n-k games where users can win vertically, horizontally, and diagonally.
- 2 players locally.
- 1 player vs. bot opponent that uses a Monte Carlo Tree Search to pick the next move.
- Unit tests.

## Get started 

- Clone locally, uses default python3 packages so it has no dependencies.
- Play 1 player vs. bot: `python main.py --players 1 --simulation_count 10`. Increase `SIMULATION_COUNT` for a more competitive game.
- Play 2 players: `python main.py --players 2`
- Run tests `pytest tests/__test_name__`

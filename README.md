# Slot Machine Game (Python)

## Overview

This is a small slot machine game I made in Python that runs in the terminal. You start with some money, place a bet, and the program "spins" three random numbers. If the numbers match, you win. If not, you lose your bet. The game keeps going until you quit or run out of money.

I made this to practice the basics of Python like loops, conditions, user input and the `random` module. It's not a fancy project, but it was fun to build and it actually works like a real (very simple) slot machine.

## Features

- Starts you off with a balance of 100 coins
- You choose how much to bet each round
- Checks your input so you can't bet more than you have, or type something weird like a negative number or letters
- Three random numbers (1 to 9) are generated on every spin
- Payouts:
  - All 3 numbers match: you win 10x your bet
  - Any 2 numbers match: you win 2x your bet
  - No match: you lose your bet
- Shows your updated balance after every spin
- Game ends when you type `q` to quit or your balance hits 0

## Technologies / Tools Used

- **Python 3** (any version 3.6 or above should work)
- **random module** (built into Python, nothing extra to install)
- VS Code / IDLE / any text editor to write and run the code
- Git and GitHub for saving the project

## How to Install and Run

1. Make sure Python is installed. You can check by opening a terminal and typing:
   ```
   python --version
   ```
   If it isn't installed, download it from [python.org](https://www.python.org/downloads/).

2. Download or clone this project:
   ```
   git clone https://github.com/your-username/slot-machine.git
   ```
   (or just download the ZIP from GitHub and extract it)

3. Go into the project folder:
   ```
   cd slot-machine
   ```

4. Run the game:
   ```
   python slot_machine.py
   ```

5. Follow the instructions on screen. Enter your bet and press Enter to spin. Type `q` whenever you want to stop.

No extra libraries are needed, so there's no `pip install` step.

## Testing

I tested this one manually by playing it and trying to break it. Here's what you can try too:

- **Normal bet:** Enter something like `10` and check that the balance goes up or down correctly.
- **Bet too high:** Enter a number bigger than your balance. It should ask you again instead of crashing.
- **Invalid input:** Type letters, symbols, or leave it empty. It should show an error message and ask again.
- **Negative or zero bet:** Try `-5` or `0`. These should be rejected.
- **Quit option:** Type `q` and the game should end and show your final balance.
- **Running out of money:** Keep betting everything until the balance is 0. The game should end with a "game over" message.
- **Win cases:** Play a few rounds to see a 2-match and a 3-match win. If you want to test faster, temporarily change the range of random numbers to `1, 2` so matches happen more often.

## Screenshots

*(Add your screenshots here)*

```
![Game start](screenshots/start.png)
![Winning spin](screenshots/win.png)
![Game over](screenshots/game_over.png)
```

## Possible Improvements

Things I might add later if I get time:

- Use symbols instead of numbers
- Make rarer numbers pay more
- Add a jackpot
- Save the high score in a file

## Author

Sai Subham Das
VIT Bhopal

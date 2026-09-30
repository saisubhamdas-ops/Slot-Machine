# Project Statement: Slot Machine Game (Python)

## Problem Statement

When you're just starting to learn Python, it's easy to read about loops, conditions, user input and the `random` module and still not really get how they work together. Small exercises feel boring and disconnected from each other. I wanted something fun that actually uses all of these ideas in one place.

So the problem I picked was: how can I build a simple, playable game that shows how basic Python concepts work together? A slot machine was a good fit because it needs random outcomes, a balance that keeps changing, input checking, and a game loop, all in a small program.

## Scope of the Project

**What the project covers:**

- A console (terminal) based slot machine game written in Python
- Starting balance, betting, spinning three random numbers and calculating winnings or losses
- Input validation so the game doesn't crash on wrong input
- A game loop that runs until the player quits or the balance reaches zero

**What the project does not cover:**

- No graphical interface (no windows, buttons or animations)
- No real money, online play or multiplayer
- No saving of progress between sessions
- No sound or images

I kept it limited on purpose so I could finish it properly and understand every line of the code.

## Target Users

- Beginners in programming who want an example of a small Python project
- Students (like me) who are learning Python and want to practice the basics
- Anyone who just wants a quick, simple game to play in the terminal for fun

It's meant for learning and entertainment only, it doesn't involve any real gambling.

## High-Level Features

- Starting balance that the player can bet from
- Bet entry with input validation
- Three random numbers generated on every spin
- Payouts based on matches: three matching numbers win big, two matching numbers win a smaller amount, no match loses the bet
- Live balance update after every round
- Option to quit anytime, and an automatic game over when the balance is zero

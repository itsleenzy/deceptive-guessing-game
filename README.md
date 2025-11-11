# Cheating Number Guessing Game

A simple Python number-guessing game with a twist: the program occasionally gives incorrect hints using weighted randomness. The player has a limited number of attempts to find the secret number, but they cannot fully trust the hints they receive.

## Features
- Random secret number between 1 and 100  
- Weighted random hints (truth vs. lie)  
- Limited number of attempts  
- Beginner-friendly Python logic  
- Uses `random.choices()` for probability weighting

## How It Works
1. The program chooses a number.  
2. The player enters a guess.  
3. The game decides — based on probability — whether to give a truthful or misleading hint.  
4. The player has a fixed number of attempts to guess correctly.  
5. The game ends when the number is found or attempts run out.

## Requirements
- Python 3.x  
- No external libraries required

## Running the Game
python game.py

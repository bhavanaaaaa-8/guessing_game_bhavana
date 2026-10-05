# Number Guessing Game
A simple Python-based number guessing game where the computer randomly generates a number, and the user keeps guessing until they find the correct number.

## Description
The program generates a random number between **1 and 100**. The user enters guesses continuously, and the program provides hints after each guess.
- If the guess is **lower** than the number, the program says **"Too low!"**
- If the guess is **higher** than the number, the program says **"Too high!"**
- When the correct number is guessed, the program displays a success message and the game ends.

## Features
- Random number generation
- Unlimited guessing attempts
- Helpful hints after every incorrect guess
- Simple and beginner-friendly Python code
- Uses a `while` loop and conditional statements

## Technologies Used
- **Python 3**
- `random` module

## How to Run
1. Make sure Python 3 is installed on your computer.
2. Download or clone this repository.
3. Open the project folder in a terminal.
4. Run the program:
```bash
python guessing_game.py
```
5. Enter your guesses and keep trying until you find the correct number.

# Example
```text
🎯 Number Guessing Game
I have chosen a number between 1 and 100.

Enter your guess: 50
Too high! Try again.

Enter your guess: 25
Too low! Try again.

Enter your guess: 37
🎉 Correct! You guessed the number!
```

## Project Structure
```text
Number-Guessing-Game/
│
├── guessing_game.py
└── README.md
```

## Concepts Used
This project demonstrates basic Python concepts such as:
- Variables
- `random.randint()`
- `while` loops
- `if`, `elif`, and `else`
- User input
- Comparison operators

## Future Improvements
Some possible improvements include:
- Counting the number of attempts
- Adding difficulty levels
- Setting a maximum number of attempts
- Allowing the user to play again
- Adding input validation

## 👨‍💻 Author

Created as a beginner Python project to practice programming fundamentals.

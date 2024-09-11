# Random Number Guessing Game

This is a simple C++ program that generates a random number and asks the user to guess it. The user is given feedback on whether their guess is too high or too low until they guess the correct number.

## How it works

1. The program generates a random number between 1 and 100 using the `rand()` function.
2. The user is prompted to input a guess.
3. The program provides feedback:
   - If the guess is higher than the random number, it outputs "Too high! Try again."
   - If the guess is lower than the random number, it outputs "Too low! Try again."
4. The program continues to prompt the user until they guess the correct number.
5. When the user guesses correctly, the program congratulates the user and displays the number.

## Prerequisites

- A C++ compiler (e.g., `g++` for Linux/MacOS or any IDE for Windows like Code::Blocks, Visual Studio, etc.)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YashPadhalni/number-guessing-game.git
2.cd number-guessing-game
3.g++ main.cpp -o guessing_game
4../guessing_game

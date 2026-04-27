# synent-task-2
The Number Guessing Game (CLI) is an interactive command-line application designed to engage users in a simple yet effective problem-solving activity. In this program, the system generates a random number within a fixed range, typically between 1 and 100, and the user is required to guess that number through successive attempts.

The core functionality of the game revolves around user interaction. The player enters guesses via the terminal, and after each input, the program evaluates the guess against the target number. Based on this comparison, it provides immediate feedback in the form of hints such as “too high” or “too low.” This feedback mechanism helps the user progressively narrow down the possible values and approach the correct answer logically.

An important feature of the game is its attempt tracking system, which records the number of guesses made by the user. Once the correct number is guessed, the program displays the total number of attempts, allowing users to evaluate their performance and encouraging them to improve efficiency in future attempts.

The program also includes input validation mechanisms to ensure robustness. If a user enters invalid data, such as non-numeric input, the system handles the error gracefully by prompting the user to enter a valid number instead of terminating abruptly. Additionally, the game provides an option to exit at any time, offering flexibility and better user control.

The game runs within a continuous loop, allowing repeated attempts until the correct number is guessed or the user decides to quit. This looping structure ensures uninterrupted gameplay and enhances the interactive experience.

From a learning perspective, this project is highly valuable for beginners as it demonstrates several fundamental programming concepts, including:

Control flow using loops and conditional statements
Random number generation to introduce unpredictability
User input handling and validation for stability
State management, such as tracking attempts and game progress

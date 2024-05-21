# Guessing Game in Python

This Python script provides two fun guessing game functions:

**1. User Guessing Game (**`guess(x)`**):**

- The computer generates a random number between 1 and `x` (inclusive).
- The user repeatedly guesses the number until they get it right.
- The program provides feedback ("too high" or "too low") after each guess.
- Upon successful guessing, the program congratulates the user and displays the number of guesses taken.

**Example Usage:**


```
guess(10)  # User guesses a random number between 1 and 10
```

**2. Computer Guessing Game (**`computer_guess(x)`**):**

- The computer thinks of a random number between 1 and `x` (inclusive).
- The user provides feedback ("too high," "too low," or "correct") for the computer's guesses.
- The computer iteratively adjusts its guesses based on the feedback until it correctly identifies the number.
- The program announces success and reveals the guessed number.

**Example Usage:**

```
computer_guess(10)  # Computer tries to guess a random number between 1 and 10
```
**How to Run:**

1. Save the script as `guess.py`.
2. Open a terminal or command prompt and navigate to the directory containing `guess.py`.
3. Run the script using `python guess.py`.

**Feel free to modify the **`x`** parameter in the function calls to adjust the guessing range.**

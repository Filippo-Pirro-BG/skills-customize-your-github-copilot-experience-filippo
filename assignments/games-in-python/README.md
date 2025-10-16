

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python. Practice string manipulation, loops, conditionals, and random selection by creating an interactive word-guessing game.

## 📝 Tasks

### 🛠️	Build the Hangman Game

#### Description
Create a Python program that lets a player guess letters to reveal a hidden word before running out of attempts.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the user
- Display the current progress (e.g., _ _ a _ _ _)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Show a win or lose message at the end

Example:
```text
Word: _ _ _ _ _
Guess a letter: a
Word: _ a _ _ _
Incorrect guesses left: 5
...etc...
```

### 🛠️	Add Replay Option

#### Description
Enhance your game to allow the player to play multiple rounds without restarting the program.

#### Requirements
Completed program should:

- Ask the player if they want to play again after each game
- Restart the game with a new word if the player chooses to continue
- Exit cleanly if the player chooses not to play again

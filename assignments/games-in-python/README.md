
# 📘 Assignment: Games in Python

## 🎯 Objective

Build the classic Hangman word-guessing game using Python strings, loops, conditionals, and user input.

## 📝 Tasks

### 🛠️ Word Selection and Display

#### Description
Implement the logic to randomly pick a secret word and display the player's current guessing progress.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list of at least 10 words using `random.choice()`.
- Display the current state of the word as underscores and correctly guessed letters (e.g., `_ p _ l e`).
- Update the display after each guess to reveal correctly guessed letters.

### 🛠️ Guess Handling

#### Description
Write the code that accepts a letter guess from the player and determines whether it is correct or incorrect.

#### Requirements
Completed program should:

- Prompt the player to enter a single letter guess.
- Check if the guessed letter is in the secret word.
- Keep track of all previously guessed letters and avoid counting duplicate guesses.
- Reduce the number of remaining attempts by 1 for each incorrect guess.

### 🛠️ Game Loop and End Conditions

#### Description
Implement the main game loop that runs until the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Allow a maximum of 6 incorrect guesses before the game ends.
- End the game with a win message when the player guesses all letters correctly. Example:
  `You won! The word was: apple`
- End the game with a lose message when attempts are exhausted. Example:
  `Game over! The word was: apple`
- Display the number of incorrect attempts remaining at the start of each turn.

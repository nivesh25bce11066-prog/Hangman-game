# Hangman-game

This project is a text-based version of Hangman. It was created to using Python  It uses a clean command-line interface with ASCII art to visualize the game progress.

======================================================================================================

Shows the hangman drawing updating visually using ASCII art as you guess.

Displays remaining lives (starts with 6) and alerts you when a guess is incorrect.

Automatically handles letter case (converts to lowercase) and informs you if you've already guessed a letter. 

=======================================================================================================

Rules of the game:

1. The computer will select a random word.

2. You will see underscores representing the letters of the hidden word.

3. Type a letter and press Enter.

4. If the letter is correct, it is revealed. If incorrect, you lose a life and the drawing progresses.

# You win by guessing the word before the drawing is complete!

=======================================================================================================
# Note:

You need to have Python installed on your computer.


# Project Files

index.py: The main script that runs the logic of the game.

hangman_art.py: A module containing the ASCII art for the logo and game stages.

hangman_words.py: A module containing the list of words used in the game.


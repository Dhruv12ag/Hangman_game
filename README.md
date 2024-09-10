# Hangman_game

A simple Hangman game where players guess letters to form a word related to the hint provided. If the player guesses incorrectly too many times, the game ends.

# Features
 Interactive Gameplay: Players can click on letters to guess the word.
 Hints: Each round provides a hint to help players guess the word.
 Incorrect Guesses: Players have up to 6 incorrect guesses before they lose the game.
       Interface

# Components:
      Word Display: Shows blank spaces for each letter of the word.
      Hint: Provides a clue related to the word. For example, "An art form using colors on a surface to create images or expressions."
      Keyboard: A clickable on-screen keyboard that allows players to select letters.
      Hangman Drawing: A visual representation of the player's progress, displayed as the stick figure is drawn with each incorrect guess.
# How to Play
Start the game: The game provides a hint and displays a series of blank spaces representing the letters in the word.
Make a guess: Click on a letter from the on-screen keyboard.
If the guess is correct, the letter appears in its respective place(s) in the word.
If the guess is incorrect, one part of the hangman drawing is added.
Win the game: Guess all the letters in the word before the hangman drawing is fully completed.
Lose the game: If the hangman drawing is fully drawn after 6 incorrect guesses, the game is over.

# Technologies Used

HTML5/CSS3: For the layout and design of the interface.
JavaScript: To handle game logic and interactions.
JSON: Optionally, for storing a collection of words and their corresponding hints.

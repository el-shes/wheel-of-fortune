# wheel-of-fortune
The project was completed as a part of the final project for a Coursera course.
This is a simplified version of the game Wheel of Fortune. The goal is to guess a phrase within a category.

Rules:
- You are playing against a computer. 
- Every player has some amount of money ($0 at the start of the game).
- Every player has a set of prizes (none at the start of the game).

- If the wheel lands on a cash square, players may do one of three actions:
     1.  Guess any letter that hasn’t been guessed by typing a letter (a-z).
         Vowels (a, e, i, o, u) cost $250 to guess and can’t be guessed if the player doesn’t have enough money. All other letters are “free” to guess.
         The player can guess any letter that hasn’t been guessed and gets that cash amount for every time that letter appears in the phrase.
         If there is a prize, the user also gets that prize (in addition to any prizes they already had).
         If the letter does appear in the phrase, the user keeps their turn. Otherwise, it’s the next player’s turn.
     
     2. Guess the complete phrase by typing a phrase (anything over one character that isn’t ‘pass’).
        If they are correct, they win the game.
        If they are incorrect, it is the next player’s turn.   

     3. Pass their turn by entering 'pass'.


The game continues until the entire phrase is revealed (or one player guesses the complete phrase).


# HANGMAN

LIVE PREVIEW: https://hangman-sedc-2023.netlify.app/

During the holidays, we all love to play games, don’t we? Why not create one yourselves and practice all the cool things you’ve learned so far? So let’s get started with a good old classic.
Create a web page that will allow the user to play the hangman game against the computer. 

The rules of hangman are this:
 - We have to guess a word by guessing individual letters. We have a set number of lives and lose a life each time we make a wrong guess.

It's a game where the unknown word is displayed as dashes, with letters fill in as we guess them. 
Thinking about this programmatically, we can see that the state of the game at any time can be represented through the use of a limited number of variables and operations on these variables.

-	At the start of the game we choose a word to be guessed. The word will be a random choice from the program out of a many options that are saved in the game. You can choose certain topic e.q. movies / TV shows.

-	We also have a number of lives, which is the total number of wrong guesses we are allowed. You set this in advance (it usually is 6 – for each part of the hangman itself (head, body, 2 arms, 2 legs). You lose a life when you have a wrong guess.


-	Finally, we have our guesses, the letters that we have guessed so far. Dashes are replaced with the guessed letters.

-	The game has three possible states - Victory (all letters guessed), Death (no more lives left) or Still Playing. All of these can be figured out using the above three variables.
It's worth emphasising that the lives, or maximum number of wrong guesses, and the word are set at the start of the game. The only thing that changes throughout the course of a game is the guessed letters, and everything else follows on from that.
BONUS: A sketch of the scaffold is added to each time there's a wrong guess. If the sketch is completed before we complete the game, then we lose!




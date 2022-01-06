# great_number_game
A site that allows a user to play a simple guessing game. Upon loading, the server will pick a number between 1-100 and store the number in session. The user is then able to guess the number. They'll be told if their guess is either too high or too low. If the correct number is guessed, the user is notified and can play again. Uses built-in Python module random to generate the random number needed for each game.

A note on using the game: in order to play multiple times it is necessary to delete the cookie created by session.
This can be done by inspecting the page > opening the application tab > deleting the cookie.

Requirements
Python 3.x with Pygame library (pip install pygame)

words.txt file containing one word or phrase per line (e.g., "hello world")

7 PNG images named hangman0.png through hangman6.png for hangman stages (0 = empty, 6 = fully drawn)​

How to Run
Place hangman.py, words.txt, and hangman PNG files in the same directory.

Run python hangman.py.

Click letter buttons to guess; game window is 700x480 pixels with green background.

Press any key after game over to restart; ESC or close window to quit.​

Game Features
26 circular buttons (A-Z) arranged in two rows, disabling after use.

Real-time word display with underscores for unguessed letters.

Hangman sprite updates on wrong guesses (limbs 0-6).

Win condition: all letters guessed; loss after 6 errors.​

Code Structure
randomWord(): Loads random line from words.txt.

redraw_game_window(): Handles drawing buttons, word, and hangman image.

buttonHit(x, y): Detects mouse clicks on buttons.

end(winner) and reset(): Game over screen and restart logic.​

# Checkers in JS
A bare minimum program to play the game of checkers<br>
<a href="https://maksimkorzh.github.io/american-checkers/">Play American checkers</a><br>
<a href="https://maksimkorzh.github.io/american-checkers/">Play Russian draughts</a>

# Features
 - 0x88 board representation
 - Brute force negamax + quiescence 7 ply fixed depth search
 - Evaluation function counts material score + positional values
 - American/Russian rule sets
 - Own web based GUI
 - Runs directly in a web browser
 - Mobile device friendly

# Estimated strength
Beats Linux QCheckers app in both variants.
From the human perspective Russian variant is probably slightly stronger
because of its sharp tactical shots.

# Limitations
 - weak endgame, especially for american variant
 - quite dumb positionally, essentially it only tries to occupy C5/F4 squares

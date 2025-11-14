# Checkers in JS
A bare minimum program to play the game of checkers:<br>
<a href="https://maksimkorzh.github.io/checkers/american-checkers.html">Play American checkers</a><br>
<a href="https://maksimkorzh.github.io/checkers/russian-draughts.html">Play Russian draughts</a>

# Features
 - 0x88 board representation
 - Brute force 7 ply fixed depth negamax + quiescence search
 - Evaluation function counts material score + positional values
 - American/Russian rule sets
 - Own web based GUI
 - Runs directly in a web browser
 - Mobile device friendly

# Estimated strength
Beats Linux QCheckers app in both variants.
From the human perspective Russian variant feels slightly stronger
because of the sharp tactical shots.
<br>
<br>
<strong>Программа русские шашки играет не меньше чем на 1250 Elo на playok, для
сравнения у блогера Владимира Вахтёрова (1 разряд) там рейтинг 1200,
то есть программа должна играть примерно на уровне 1-го разряда.</strong>

# Limitations
 - weak endgame, especially for American variant
 - quite dumb positionally, essentially it only tries to occupy C5/F4 squares

# circpong
Basic gdevelop game, a ponglike where you spin in a circle and try to survive as long as possible

D to rotate clockwise, A to rotate counterclockwise, space to begin. The ball will move slowly at first, but speed up a bit with each hit (the formula is (log2(hits+3)*280)^0.83, if you're curious)
Each star gives a score when hit, and more score for each hit in a combo. A combo is broken when you hit a paddle without having hit any stars since the last paddle hit. This makes the bonus hard to maintain with multiball
if all balls leave, you lose, and your high score is saved for the rest of the session

Good luck!

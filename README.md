# dartboard-solver

Solver for the Billiard Room dartboard puzzles from the [Blue Prince] (https://www.blueprincegame.com/) video game.

Live deployment here: [Blue Prince Dartboard Solver](https://caprica.github.io/blue-prince-dartboard-solver/)

## Why?

> "Why make this? Isn't the puzzle fun, doesn't this spoil it?"

Yes, the puzzle *is* fun, and it's not *really* all that difficult once you've done 200 of them and know how they work.

But I *have* done 200 of them, and honestly, that's enough for me.

Also, and really this is the main reason - I love writing code, and this was a fun coding challenge.

## Instructions

It should be very simple:

* Use the mouse to click, or touch, the segments on the dartboard to match the puzzle.
* You can click/touch the bullseye, all of the "beds", and the outer ring.
* Repeated clicks/touches cycle - for the bullseye and the beds it cycles add, subtract, multiply, divide, for the outer ring it cycles double, half, ignore and reverse digits
* Press and hold to toggle between full score and 1/3.
* Set the bullseye modifiers by clicking/touching the boxes below the board.
* Repeated clicks/touches cycle the bullseye modifiers through square, reverse digits, nearest 1, nearest 10 and nearest 100.
* Press the "Reset" button to clear the board and start again.

If the board configuration is valid, the solution score will be highlighted.

No keyboard support (yet?) I'm afraid.

## Mobile

It is mostly usable on mobile devices, but the touch interactions can be a litle awkward. Pinch-to-zoom is supported and can help a lot.

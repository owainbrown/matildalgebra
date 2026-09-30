# Matildalgebra

A maths game for Year 2, set in Miss Honey's classroom. It follows the White Rose Maths autumn term: place value within 100, and addition and subtraction within 100.

Every right answer puts a book on the library shelf, with the maths fact from that question written inside (tap a book to read it, or have it read aloud). Get three in a row first time and the chalk starts writing by itself. The Trunchbull's Test mixes all the lessons: get 8 out of 10 right first time to beat her.

## Lessons

- **Tens and Ones**: fill the empty box in `54 = 50 + ☐`, with base-ten blocks to help. Harder levels add tens-and-ones boxes, comparing with `<`, `>` and `=`, and splitting a number a different way (`54 = 40 + 14`).
- **Number Lines**: where is the arrow pointing? The lines go 0–20, 0–100 in tens, then 10-wide segments, fives and twos, and finally estimating on a mostly blank line.
- **Counting Patterns**: count in 2s, 5s and 10s, forwards and backwards, with 3s and two missing boxes at level 3.
- **Adding and Taking Away**: from facts within 20 and number bonds to 10 and 100, up to 2-digit ± 1-digit and 2-digit numbers that cross a ten. Explanations use the empty number line, jumping to the next ten first.

Each lesson has three levels. Scoring 9 or 10 right first time moves it up a level automatically. Grown-ups can change the level with the − and + buttons on the lesson list.

The first wrong answer gives another go. A second wrong answer shows the answer with a picture explaining it.

There are no timers anywhere. After a right answer the game waits for any speaking to finish before moving on, or, if you prefer, waits for a Next button.

Questions are read aloud with the browser's speech. Novelty and robotic voices (the iPad ones like Grandma, Rocko and Bubbles) are filtered out and the best British voice is chosen; a grown-up can pick a different voice on the home screen. Sound can be switched off on the home screen or from the button during a lesson.

## Running it

It's a single static page (`index.html`) with no build step, served by GitHub Pages from `main`. Progress is saved in the browser's local storage.

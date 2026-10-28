# Reverse Flap — REMIX 02

A browser game inspired by Flappy Bird, with a major change: **the bird flies automatically and the player controls the pipe openings**.

## Play

Download this GitHub repository as ZIP, extract it, then open `index.html` in Chrome, Safari, or another modern browser. No server or extra files are needed.

Click **Start game**. Hold **Up/Down arrow** or **W/S** to move the pipe opening. Onscreen buttons work too. Position the opening around the bird as the pipe moves toward it. Each safe pipe earns a point. **Pass five pipes to win**, or collide with a pipe to lose. Click **Play again** to start a new round; **Restart** returns to the starting screen.

## What changed for REMIX 02

Added a clear five-pipe win condition and a separate victory message. Fixed replay handling so a finished round resets before a new one starts, rather than carrying over its score. The reverse-control mechanic remains the main challenge.

## Testing

See `REMIX02_Test_Plan.txt` for five repeatable checks and expected results. Complete the actual browser tests and classmate playtest yourself; do not treat expected results as completed test evidence.

## Credits

Game concept and creative decisions: student. Code and documentation assistance: ChatGPT. Graphics: original shapes drawn in JavaScript. No external art or audio.

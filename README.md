# Reverse Flap — REMIX 03 (Final)

A small original-shapes browser game inspired by Flappy Bird. **The twist:** the bird flies on its own; the player moves the **pipe openings**, not the bird.

## Open and play

Download the repository ZIP from GitHub, extract it, and double-click `index.html`. No installation, internet connection, or other assets are needed. Click **Start game**. Hold **Up / Down** or **W / S**, or hold the on-screen arrow buttons, to move the pipe gap. There is **no score limit**: keep passing pipes to earn points and beat your best score. Touch a pipe to end the round. **Play again** starts a fresh round; **Restart** returns to the opening screen.

## Final improvement

Fixed an abrupt control issue: the gap used to jump back to the center whenever a new pipe appeared, even if the player was positioning it. Now the opening **stays where the player left it** between pipes. Also cleared held keyboard controls when a round ends, and clarified the opening directions.

## Classmate feedback and change

A classmate said the game was understandable but wanted to keep playing instead of winning automatically after five pipes. The five-point win limit was removed so the round continues until a collision. **Retest needed:** pass at least six pipes, collide, and restart; confirm the score continues, the collision ends the round, and the score resets.

## Known limitations

One fixed difficulty level. This is a small single-screen game with no audio.

## Credits

Game concept and gameplay choices: student. Coding and documentation assistance: ChatGPT. All graphics are original JavaScript shapes; no outside art or audio.

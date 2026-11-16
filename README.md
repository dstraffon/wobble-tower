# Wobble Tower

A small physics game: stack smiley blocks on a tiny island and see how high you can build before three of them fall into the sea.

**Play it:** https://dstraffon.github.io/wobble-tower/

## How to play

- Drag the block from the Next slot (or press anywhere in the sky) and let go to drop it.
- Rotate with the round buttons, the arrow keys, A/D, or the scroll wheel. You can rotate while holding a block.
- Tap Hold (or press H) to stash a block and swap it back in later.
- Your score is the tower's peak height in metres. Each block that splashes costs a heart.

Works with touch and mouse, on phones and desktops.

## How it's built

One `index.html` file, no build step.

- Physics: [Matter.js](https://brm.io/matter-js/) 0.19, loaded from cdnjs
- Drawing: HTML canvas
- Sound: synthesised with the Web Audio API, so there are no audio files
- Scores: your top five runs are kept in the browser's local storage

To run it locally, open `index.html` in a browser.

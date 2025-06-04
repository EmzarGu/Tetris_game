# Tetris_game

This repository contains a simple 3D Tetris well rendered using [three.js](https://threejs.org/). The scene is viewed from directly above the centre of the well so the bottom appears as a small square. All five inner surfaces (floor and four walls) are drawn using green grid lines. The playfield measures 5×5 cells and is 12 cells deep.

A random tetromino spawns in the well and can be moved and rotated using the keyboard. Each shape uses a distinct color and is drawn semi-transparent with white edges while falling, becoming fully opaque when it lands. Use the arrow keys to slide the piece along the playfield, while **W**, **A**, **S**, and **D** rotate it around the X and Y axes. The piece automatically falls one cell every two seconds until it meets an obstacle or the floor. When a piece lands, a new one appears at the top if there is room; otherwise the game stops. Movement is clamped to keep pieces inside the well, and rotations automatically shift the piece inward if needed so it never goes out of bounds. When a layer fills completely it disappears and the blocks above drop down. Each cleared layer increases the speed level, which shortens the drop delay and awards that level value to your score. The overlay shows your score, current level and highest score for the session. When the well fills and no new piece fits, "Game Over" appears. Press **P** or click Pause to pause/resume, tap the **spacebar** to drop the active piece quickly, press **R** or click Reset to start a new game while keeping the high score, and press the **+** key to manually raise the level.

## How to view

Open `src/index.html` in a modern web browser. The page loads three.js from a CDN and renders the Tetris well.

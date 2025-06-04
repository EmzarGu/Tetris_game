# Tetris_game

This repository contains a simple 3D Tetris well rendered using [three.js](https://threejs.org/). The scene is viewed from directly above the centre of the well so the bottom appears as a small square. All five inner surfaces (floor and four walls) are drawn using green grid lines. The playfield measures 5×5 cells and is 12 cells deep.

A random tetromino spawns in the well and can be moved and rotated using the keyboard. Each shape uses a distinct color and is drawn semi-transparent with white edges while falling, becoming fully opaque when it lands. Use the arrow keys to slide the piece along the playfield, while **W**, **A**, **S**, and **D** rotate it around the X and Y axes. The piece automatically falls one cell every two seconds until it meets an obstacle or the floor. When a piece lands, a new one appears at the top if there is room; otherwise the game stops. Movement and rotation are clamped so pieces never leave the well. This is an early step toward a complete 3D Tetris game.

## How to view

Open `src/index.html` in a modern web browser. The page loads three.js from a CDN and renders the Tetris well.

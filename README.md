# Tetris_game

This repository contains a simple 3D Tetris well rendered using [three.js](https://threejs.org/). The scene is viewed from directly above the centre of the well so the bottom appears as a small square. All five inner surfaces (floor and four walls) are drawn using green grid lines. The playfield measures 5×5 cells and is 12 cells deep.

A single tetromino shape is spawned in the well and can be rotated using the keyboard. To make its orientation easier to see it is rendered as a wireframe cube assembly with a slight transparency. Use the arrow keys to rotate the piece in different directions. This is an early step toward a complete 3D Tetris game.

## How to view

Open `src/index.html` in a modern web browser. The page loads three.js from a CDN and renders the Tetris well.

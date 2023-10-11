# Cricket Cum Minesweeper Game

## Table of Contents
1. [Introduction](#introduction)
2. [Game Design](#game-design)
    - [Main Page](#main-page)
    - [Singleplayer Page](#singleplayer-page)
    - [Multiplayer Page](#multiplayer-page)
    - [OUTs and Powerups](#outs-and-powerups)
4. [Implementation](#implementation)
    - [Single Player](#single-player)
    - [Multiplayer](#multiplayer)

## Introduction
This project is about creating an online Cricket Cum Minesweeper game. The game is developed using HTML, CSS, and JavaScript. The project aims to combine the fun of cricket with the puzzle-solving challenge of Minesweeper.

## Background
The project started with a study of existing online Minesweeper games and an understanding of HTML, CSS, and JavaScript. Modifications were made to existing code, and debugging was assisted by using ChatGPT.

## Game Design
### Main Page
The main page allows users to input the size of the grid and choose between single-player and multiplayer modes. A "Start Game" button initiates the game.


### Singleplayer Page
In the single-player game, 11 fielders are hidden within the grid. Clicking on the grids reveals your score on that grid. You can continue the game until you click on a grid with a fielder. Lucky players may receive power-ups that double their current score.


### Multiplayer Page
The multiplayer game consists of multiple pages, where players take turns. The final page shows the scoreboard and announces the winner or ties.

### OUTs and Powerups
OUTs and power-ups are integral to the gameplay, affecting the scores and game outcomes.


## Implementation
### Single Player
In the single-player game, a grid is created with 11 fielders randomly placed. JavaScript functions handle cell clicks, game ending, and power-ups. The game calculates scores and displays them on the grid.

### Multiplayer
The multiplayer game involves two HTML pages, Multiplayer.html and supmul.html. Players enter their names and scores are tracked. The game progresses based on the number of players. A winner or ties are declared at the end.

For detailed code and functions, please refer to the **Code** and **Report**

For a more detailed look at the code and its functionality, please refer to the referenced sources and the provided source code in the project repository.

---

**Note**: Replace `link_to_image` and `link_to_repository` with actual links to images and your GitHub repository where the project code is hosted.

This README provides a brief overview of the project. Users or developers interested in exploring the project in more detail can refer to the source code and other resources linked in the README.

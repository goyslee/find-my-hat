# Find Your Hat

## Overview
"Find Your Hat" is an interactive terminal-based game where the player navigates a field to find their hat. It's a part of the backend section in Codecademy's Full-Stack Engineer Career Path. The game is built using Node.js and can be played directly in the terminal.

The field consists of a grid, with the following elements:
- A hat (^) which the player needs to find
- Holes (O) which the player must avoid
- A path (*) indicating where the player has been
- The field itself (░) which represents safe spots to step on

## How to Play
The player starts at the top-left corner of the grid and moves one step at a time in an attempt to reach the hat. The player must not fall into any holes or step outside the boundaries of the field. Moves are made by entering 'U', 'D', 'L', or 'R' for up, down, left, or right, respectively.

## Win Condition
The game is won when the player successfully navigates to the position of the hat.

## Lose Conditions
The game is lost if the player:
- Moves onto a hole
- Steps outside the field boundaries

## Running the Game
To run the game, you need to have Node.js installed on your computer. Clone the repository, navigate to the project directory in your terminal, and run the following command:

```bash
node main.js
```

# Project Structure
- `main.js`: The entry point of the application containing all the game logic.

# Technologies Used
- JavaScript
- Node.js
- `prompt-sync` Node.js library for synchronous input handling

# Project Status
This game is a project exercise as part of the backend section of the Codecademy Full-Stack Engineer Career Path curriculum.

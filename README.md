# Dice Game Implemented in Java 8

## Overview 

This project is a **console-based dice game for two players** developed in **Java 8** as part of an Object-Oriented Programming coursework assignment. The game is played in turns by two players sharing the keyboard, and the objective is to achive the **highest cumulative score after seven rounds**.

Each player has:

- 7 rounds
- up to 3 throws per sound
- 3 dice per throw
- 7 scoring categories, where each category can only be used once during the whole game.

The project demonstrates a combination of **game logic, user interaction, scoring rules, input validation, and turn-based flow control** in Java.

## Key Purpose 

The purpose of this project is to implement a small but complete Java game that demonstrates:

- turn-based game programming
- array-based score tracking
- random dice generation
- category-based scoring
- console input handling
- rule enforcement across multiple rounds

It also shows how a simple game can include both **luck and strategy**, because players must choose when to lock in a category and when to defer for another throw.

## Game Rules

The game follows these main rules:

- The game is played by **2 players**
- The game lasts for **exactly 7 rounds**
- In each round, each player may choose to **throw or forfeit**
- A player can have **up to 3 throws**
- After a throw, the player may either:
    - **select a category**, or
    - **defer** and throw again
- Each scoring category can only be selected **once per player**
- The final winner is the player with the **highest total score** after round 7.

The categories are:

  - Ones
  - Twos
  - Threes
  - Fours
  - Fives
  - Sixes
  - Sequence (worth 20 points if achived)
 
  ## What the Program Does

When a program starts, it displayes a welcome message explaining the rules and then asks the user whether to start or exit the game. If  user starts, the program creates score arrays for both players, displays the score table, and begins the seven-round loop.

For each round:

- Player 1 takes a turn
- Player 2 takes turn
- each player can throw or forfeit
- after each throw, the player can select a category or defer
- the selected category score is stored in that player's score array
- the scoreboard is uploaded after the round ends.

At the end of round 7, the program sums both players' scores and annouces the winner. 

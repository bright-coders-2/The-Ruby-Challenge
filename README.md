# The Ruby Challenge

To complete this challenge you are required to fulfill the following 3 tasks

# 1 Tic Tac Toe

## Objective

In order to practice what we have learned regarding OOP and best practices, let's implement a Tic-Tac-Toe (Gato in Spanish) game!

## Rules
    • Two players represented with X and O.
    • First time the game is played, X startsEach player alternate turns to put a mark in the board on any available slot.
    • The game ends when either one of the players matches three marks in a horizontal, vertical or diagonal row or 
    there are no more moves available.
    • Once the game finishes, players are asked if they want to play again. If they do, the player who lost the previous 
    match starts. In case of a draw, the player who did the second-to-last movement starts.

## Considerations
    • Will the logic have to change if I want to play on a N x N board instead of the original 3 x 3?
    • Gem are supposed to be used by other programmers so they need to be well documented and tested.

## Game instructions 

The game start ask you for the board size, after that the game ask the cell position to the player in turn, and that step is repeat
until there is a winner or a draw. When any of these conditions are reached display a message and after that the game ask if they want
to play again, if the answer is yes the game start again, otherwise the game ends.

# 2 Ruby Conway's game of life

## The Game
The Game of Life is not your typical computer game. It is a 'cellular automaton', and was invented by Cambridge mathematician John Conway.

This game became widely known when it was mentioned in an article published by Scientific American in 1970. It consists of a collection of cells which, based on a few mathematical rules, can live, die or multiply. Depending on the initial conditions, the cells form various patterns throughout the course of the game.

## Requirement
- You must implement the game of life using ruby

# 3 Writting a Ruby Gem

You must write a document that details the process of writing a Gem using Ruby. The document must be written in a way so others can follow it to create a ruby gem.


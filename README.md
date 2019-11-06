# Connect4

## Introduction

This was a second year project where we had to make a game in C++. I made Connect4, the key feature is that one can play against the computer, using a rudimentary AI system where the computer chooses its next move by computing all of the next possible moves given the current move by the user and the state of the board. It chooses the column that has the most possible wins for the computer and least possible wins for the user.

In practice, it provides a reasonable challenge, but with little strategy, once can defeat the computer.

## Installation and requirements

No third party libraries are used, the only requirement is a terminal that supports ANSI escape codes, and of course a C++ compiler. The following command can be used to compile (tested on Clang, should work with GCC too):

```
g++ aiplay.cpp board.cpp implementation.cpp main.cpp --std=c++98 -o main
```

## Usage

Run ```./main```, follow the relevant prompts to start a new game, and best of luck.

## Report

A report documenting how the programme works is in ```report.pdf```. It follows this specification:

### Section A

> Describe your Part 1 game project, including your game idea and game play and all the features you implemented. This should include:
> 1. A class diagram, showing all the classes, inheritance and composition relationships. (up to 5 marks)
> 2. A description of your game idea and the game play, including short code extracts of how you implemented it. (up to 5 marks)
> 3. Modify your program to copy all your screen output to a text file (using ofstream) and include this text file in the report. (up to 5 marks)

### Section B

>1. Describe how you would extend your game with more advanced gameplay and features (up to 5 marks)
>2. Provide a new class diagram to depict this (up to 5 marks)
>3. Provide the C++ class definitions for your new game, including all attributes and method definitions (including constructors and destructor). (up to 5 marks)
>4. Provide a pseudocode explanation of each method you have listed (up to 10 marks)

### Section C

>1. Describe and provide the class diagrams and C++ class definitions for another game that is completely different from the one you did for Part 1, (up to 10 marks)
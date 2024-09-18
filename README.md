# Hangman Game 🎯

Welcome to the **Hangman Game**! This is a simple console-based implementation of the classic word-guessing game. The game is entirely hardcoded and serves as a fun project to demonstrate basic programming concepts like loops, conditional statements, and user input handling.

## Table of Contents

- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hangman is a word-guessing game where the player must guess the word letter by letter within a limited number of attempts. If the player guesses incorrectly too many times, the game ends and the player loses.

This project is designed for beginners who are learning the basics of coding and want to see how a simple game can be implemented using fundamental programming concepts.

## How to Play

1. The game randomly selects a word (hardcoded).
2. You have to guess the word by entering one letter at a time.
3. You have a limited number of incorrect guesses before the game ends.
4. If you guess all the letters in the word correctly, you win!

## Features

- **Console-based interface**: Simple text-based input and output.
- **Hardcoded word list**: A set of predefined words is used for the game.
- **Basic game logic**: The game handles guessing, tracking incorrect attempts, and displaying the current progress.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/shatakshi-sinha/Hangman.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Hangman
    ```

3. Run the script:

    ```bash
    python hangman.py
    ```

> **Note:** Ensure you have Python installed on your system.

## Usage

Simply run the script and follow the prompts in your terminal. Enter one letter at a time to guess the word. The game will display the current state of the word after each guess and inform you of how many incorrect guesses remain.

## Project Structure

hangman-game/
│
├── hangman.py          # Main script containing the game logic  
├── README.md           # Project documentation (this file)  
└── words.py            # Optional file if the word list is separated from the main script  


## Contributing

This is a basic project for learning purposes, but feel free to fork the repository and add your own improvements. Whether it's adding a graphical interface or enhancing the word list, contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

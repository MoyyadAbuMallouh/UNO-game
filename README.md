# Uno Game Engine

## Project Overview

This project is an Uno game engine built in Java, designed for developers to create and customize their own Uno game variations. The engine provides a flexible framework that allows for the extension of game rules, card types, and game mechanics with minimal effort. [cite: 1, 12]

The core of the engine is an abstract `Game` class that developers can extend to implement specific game variations by overriding abstract methods. [cite: 13, 14] The engine aims to minimize programming efforts by including a predefined set of game rules that developers can select from. [cite: 14]

## Game Background

Uno is a card game typically played by 2-10 players, using a deck of 108 cards. [cite: 3] The cards are divided into:
* Numbered cards (0-9) [cite: 3]
* Action cards (Reverse, Skip, Draw Two) [cite: 3]
* Wild cards (Wild, Wild Draw Four) [cite: 3]

Each player starts with 7 cards. [cite: 4] The game can have multiple variations, such as additional card types, different numbers of starting cards, or unique penalty rules. [cite: 7, 8, 9, 10] For the basic rules, please refer to the [official Uno rules on Wikihow](https://www.wikihow.com/Play-Uno) (as specified in the project guidelines). [cite: 5]

## Engine Design & Features

* **Extensibility:** Designed to allow developers to easily add new game rules, cards, or card dealing mechanisms. [cite: 16]
* **Abstract `Game` Class:** Developers create new game variations by extending this class and implementing its abstract methods. [cite: 13, 14]
* **`play` Method:** The `Game` class includes a `play` method to simulate the game. [cite: 15]
* **Predefined Rules:** Includes a set of common game rules for developers to choose from. [cite: 14]
* **`GameDriver` Class:** Contains the `main` method to instantiate a game object and start the game by invoking the `play` method. [cite: 17, 18, 19]
* **Example Variation:** The engine includes at least one concrete example of an Uno game variation. [cite: 21]

## Getting Started

1.  Familiarize yourself with the Uno game and its variations. [cite: 11]
2.  To create a new Uno game variation:
    * Create a new Java class that extends the abstract `Game` class.
    * Implement the necessary abstract methods to define your game's specific rules and logic. [cite: 14]
3.  Use the `GameDriver` class to run your game:
    * Instantiate your game variation object. [cite: 19]
    * Call the `play()` method on the game object. [cite: 19]
    * Optionally, use a scanner to get players' names. [cite: 20]

## Technologies Used
* Java
* Object-Oriented Programming (OOP) principles [cite: 12]

## Project Deliverables (as per assignment)
* Source code (`.java` files)
* A report detailing:
    * Object-oriented design [cite: 23]
    * Design patterns used
    * Defense against clean code principles (Uncle Bob) [cite: 24]
    * Defense against "Effective Java" Items (Joshua Bloch)
    * Defense against SOLID principles [cite: 25]
* A demo video (max 10 minutes, preferably under 7) showcasing a game run, design explanation, code organization, extensibility, and reusability. [cite: 26, 29] The video should also include a self-introduction. [cite: 27, 28]
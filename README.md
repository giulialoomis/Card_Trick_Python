# card-trick-python

## Overview
This Python program simulates a card trick where the user selects a card from a dealt set of cards, and through a series of interactions, the program identifies the user's chosen card. The trick involves dealing cards into three columns, prompting the user to select the column containing their card, and then rearranging and redealing the cards multiple times. After three rounds of selection, the program reveals the user's "secret card."

## Features
- Deals cards into three columns and prompts the user to select which column contains their chosen card.
- Rearranges and redeals cards based on user input to simulate the card trick process.
- Repeats the card selection process over three rounds to refine the guess.
- Reveals the user's selected card as the "secret card" at the end of the trick.

## Technologies Used
- **Python**: The entire program is written in Python, leveraging basic logic structures, loops, and user input handling.

## How It Works
1. The program initially deals a set of cards into three columns, displayed row by row.
2. The user is prompted to select the column that contains their card by entering the column number (0, 1, or 2).
3. The program rearranges the columns, ensuring that the chosen column is picked up second.
4. After three rounds of dealing and user selection, the program reveals the user's "secret card."

## Running the Program
1. Clone this repository to your local machine.
2. Run the Python script using the command `python card_trick.py`.
3. Follow the on-screen instructions to select your card and see the trick unfold.

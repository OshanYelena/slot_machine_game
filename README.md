# Slot Machine Game

## Overview

This Python script simulates a simple slot machine game where players can deposit money, place bets on multiple lines, spin the slot machine, and check their winnings. The game includes the following features:

- Deposit money to start playing.
- Choose the number of lines to bet on.
- Place a bet amount for each line.
- Spin the slot machine and display the result.
- Check for winnings and update the balance accordingly.
- Continue playing until the player decides to quit.

## Requirements

- Python 3.x


## How to Run

1. Ensure you have Python installed on your machine.
2. Download the script `slot_machine_game.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory where `slot_machine_game.py` is located.
5. Run the script by typing `python slot_machine_game.py`.

## Gameplay Instructions

1. **Deposit Money**: When prompted, enter the amount of money you want to deposit to start playing.
2. **Select Lines**: Enter the number of lines (1 to 3) you want to bet on.
3. **Place Bet**: Enter the amount you want to bet on each line. The amount must be between $1 and $100.
4. **Spin the Slot Machine**: Press enter to spin the slot machine. The results will be displayed along with any winnings.
5. **Continue or Quit**: After each spin, you can choose to spin again or quit the game. If you choose to quit, your remaining balance will be displayed.

## Code Explanation

### Constants and Configuration

- `MAX_LINES`: Maximum number of lines a player can bet on.
- `MAX_BET`: Maximum bet amount per line.
- `MIN_BET`: Minimum bet amount per line.
- `ROWS` and `COLS`: Dimensions of the slot machine.
- `symbol_count`: Dictionary containing the count of each symbol.
- `symbol_values`: Dictionary containing the value of each symbol.

### Functions

- `check_winnings(columns, lines, bet, values)`: Checks the winnings based on the slot machine spin, number of lines bet on, and bet amount. Returns the total winnings and the winning lines.
- `get_slot_machine_spin(rows, cols, symbols)`: Generates a random spin for the slot machine.
- `print_slot_machine(columns)`: Prints the slot machine columns in a readable format.
- `deposit()`: Prompts the player to deposit money and returns the deposited amount.
- `get_number_of_lines()`: Prompts the player to enter the number of lines to bet on and returns the number of lines.
- `get_bet()`: Prompts the player to enter the bet amount per line and returns the bet amount.
- `spin(balance)`: Manages the betting process, including checking if the player has enough balance, spinning the slot machine, and calculating the winnings.
- `main()`: The main function to run the game, manage the balance, and handle user input to continue or quit the game.

### Sample Output

```plaintext
What would you like to deposit? $100
Current Balance is $100
Enter the number of lines to bet on (1- 3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20
C | D | A
B | C | D
A | B | C
You won $0.
You won on lines
Current Balance is $80
Press enter to spin (q to quit).

```

## Contact

For any questions or comments, please contact the project maintainer.





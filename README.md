# Slot Machine Game

This is a simple command-line slot machine game written in Python.

## Getting Started

To run the game on your local machine, follow the steps below:

1. Make sure you have [Python](https://www.python.org/downloads/) installed on your computer.

2. Clone this repository to your local machine using the following command: git clone https://github.com/bharghavasagar2/slot-machine-game.git

3. Navigate to the project directory:

4. Run the game by executing the Python script:

## Gameplay

1. Deposit: At the beginning of the game, you'll be asked to deposit an amount. Enter the amount you want to start playing with.

2. Betting: Next, you'll be prompted to enter the number of lines you want to bet on and the amount you want to bet on each line. The total bet is calculated based on your input.

3. Spinning: The slot machine will display the results of the spin. Each column will show a randomly selected symbol (A, B, C, D). The game will check for winning combinations on the selected lines.

4. Winnings: If you win on any line, your winnings will be displayed along with the line numbers where you won.

5. Continue Playing: After each spin, you have the option to play another round by pressing Enter. If you want to quit the game, type 'q' and press Enter.

## Rules

- The slot machine has 3 rows and 3 columns.
- The game supports betting on 1 to 3 lines.
- The symbols and their corresponding values are as follows:
- A: Value 5
- B: Value 4
- C: Value 3
- D: Value 2

## Customize

Feel free to customize the `MAX_LINES`, `MAX_BET`, `MIN_BET`, `ROWS`, `COLS`, `symbol_count`, and `symbol_value` constants in the Python script to modify the game rules and behavior.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was inspired by our love for Python and simple games.
- Thanks to [OpenAI](https://openai.com) for the GPT-3.5 model, which helps in generating this README file.

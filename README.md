# Rust Guessing Game

This is a simple number guessing game written in Rust. The program randomly generates a secret number between 1 and 100, and the player is prompted to guess the number. The program provides feedback whether the guess is too low, too high, or correct. The game continues until the player guesses the correct number.

## How It Works

1. The program generates a random number between 1 and 100.
2. The player is prompted to input a guess.
3. After each guess, the program checks if the guess is:
    - Too small
    - Too big
    - Correct
4. The game ends when the correct number is guessed.

## Prerequisites

To run this program, you need to have the Rust programming language installed. If Rust is not installed on your machine, you can follow [the official installation guide](https://www.rust-lang.org/tools/install).

## How to Run

1. Clone the repository or copy the code into a file named `main.rs`.
2. Open a terminal in the project directory.
3. Run the following command to execute the program:

    ```bash
    cargo run
    ```

4. The program will start, and you will be prompted to guess the secret number.

## Dependencies

This project uses the following dependencies:
- [rand](https://crates.io/crates/rand) crate for generating random numbers.

To add the `rand` crate to your project, include it in your `Cargo.toml` file:

```toml
[dependencies]
rand = "0.8"

## Example

When you run the program, you will see something like this:

### Explanation:

1. The program starts by asking the user to guess a number.
2. The user guesses **5**, but it's too small.
3. The user then guesses **50**, which is too big.
4. Finally, the user guesses **30**, which is the correct number, and the game ends with a win.

You will need to repeat this process until you guess the correct number.



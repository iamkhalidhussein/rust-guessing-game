# 🎯 Rust Guessing Game

A simple command-line guessing game built with Rust.  
The program randomly generates a number between 1 and 100, and you try to guess it!

## 🛠 Features

- Random number generation using `rand` crate
- User input via standard input
- Friendly feedback: "Too small!", "Too big!", or "You win!"
- Loops until the correct guess
- Handles invalid input gracefully

## 📦 Requirements

- [Rust](https://www.rust-lang.org/tools/install) (1.70+ recommended)


## 🚀 Run the Project

1. **Clone the repo**  
   ```bash
   git clone https://github.com/iamkhalidhussein/rust-guessing-game.git
    ```
    ```
   cd rust-guessing-game
   ```
    ```
   cargo run
   ```

📁 Project Structure

```
├── src/
│   └── main.rs        # Game logic
├── target             # holds all the build artifacts and intermediate files
├── Cargo.toml         # Project configuration
├── .gitignore         # Files ignored by git
└── README.md          # This file
```
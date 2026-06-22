https://drive.google.com/file/d/1B1sXWGQK2nLEl6EpFB4YWKVgQHAirhlZ/view?usp=sharing
# PR. 1 Fundamental Booster - Personal Data Collector

This project is a command-line Python application designed to collect user data, analyze its fundamental properties (such as data types and memory addresses), and perform basic calculations based on user input.

## Features
- Collects personal details (Name, Age, Height, Favourite Number).
- Displays the exact Python data type (`str`, `int`, `float`) for each input.
- Displays the memory address (`id()`) of the variables.
- Estimates the user's birth year based on the current system year and provided age.

## Assumptions
- The system assumes the current year is 2026 for calculating the approximate birth year.
- User inputs for Age, Height, and Favourite Numbers are expected to be in correct formats (`int` and `float`) to avoid termination.
- The memory addresses displayed will vary every time the script runs as they are dynamically allocated by the Python interpreter.

## How to Run
1. Ensure you have Python installed on your system.
2. Clone this repository or download `main.py`.
3. Open your terminal/command prompt and run:
   ```bash
   python main.py

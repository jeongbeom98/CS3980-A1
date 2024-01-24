# CS3980-A1: Assignment 1 - Python Refresher

## Introduction
This repository contains my solutions for Assignment 1: Python Refresher in the CS:3980:0001 Spr24 course. It is comprised of two parts: 
1. An `echo.py` script that imitates a real-world echo.
2. A `fib.py` script that calculates the Fibonacci sequence with an optimized execution time using decorators.

## Part 1: Python Programming Basics - Echo

The `echo.py` script contains a function that simulates an echo effect. Given a word or phrase, it "echoes" the input, with each repetition losing the last character to simulate a fading echo.

### Example Output
python echo.py
Yell something at a mountain: Helloooo
ooo
oo
o
.
![Echo Function Output](echo.png)

## Part 2: Python Decorator Implementation - Fibonacci Sequence

The `fib.py` script computes the nth Fibonacci number using a recursive approach. Performance is enhanced with the `lru_cache` decorator, which caches the results of function calls.

### Optimizations
- **`lru_cache`**: Caches results of recursive calls to avoid redundant computations.
- **Timer Decorator**: Records the execution time of each function call.

### Timing Output
The execution times for calculating Fibonacci numbers are as follows:

![Timing Output for Fibonacci Calculation](fib.png)
Finished in 0.0000005000s: f(1) -> 1
...
Finished in 0.0136379000s: f(100) -> 354224848179261915075

## Running the Code
To execute the scripts, follow these steps:
1. Clone this repository.
2. Navigate to the cloned directory.
3. Execute `python echo.py` or `python fib.py` in the terminal.

## Feedback
Feedback and suggestions for improvement are always welcome. Please feel free to create an issue or submit a pull request.

## Contact Information
- **Name:** JB (Jeongbeom) Lee
- **Email:** [jeongbeom98@gmail.com](mailto:jeongbeom98@gmail.com)
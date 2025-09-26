Wordle AI Exploration 
=========

This repository contains my research and implementation of different AI strategies for solving the popular word game Wordle. The project compares heuristic approaches, frequency-based strategies, and information-theoretic (entropy-based) methods to evaluate how AI can efficiently solve Wordle puzzles.

Project Overview

Wordle is a word-guessing game where players must find a hidden five-letter word in six tries or fewer. Each guess provides color-coded feedback:

Green = correct letter, correct position
Yellow = correct letter, wrong position
Gray = incorrect letter

The challenge for AI is to minimize the number of guesses by choosing words strategically.

This project explores:

A rule-based solver (basic filtering with logical constraints).

A frequency-based solver (using letter frequency across word lists).

An entropy-based solver (maximizing expected information gain per guess).

Goals

Compare accuracy and efficiency across solver types.

Analyze trade-offs between computational cost and performance.

Understand how information theory applies to word-based puzzles.

Methods

Implemented in Python (Google Colab/Jupyter Notebook).

Used standard libraries: NumPy, pandas, matplotlib.

Word list derived from official Wordle dictionaries.

Evaluation based on the average number of guesses to solve.

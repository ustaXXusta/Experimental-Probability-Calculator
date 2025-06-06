# Dice Probability Calculator
https://ustaxxusta.github.io/Experimental-Probability-Calculator/
## Overview
The **Dice Probability Calculator** is a web application built with Javascript that calculates experimental probabilities of dice roll outcomes. It simulates rolling a standard six-sided die and tracks the frequency of each number (1–6) to compute probabilities based on user-initiated rolls.

## Features
- **Real-Time Probability Calculation**: Updates probabilities after each roll based on the number of times each face (1–6) appears.
- **Interactive Interface**: Users can roll a virtual die with a button click and view results instantly.
- **Responsive Design**: Neumorphic UI with a clean, modern look, fully responsive for various screen sizes.
- **Code Generation**: Optionally generates Hammerspoon-compatible code for key bindings (e.g., to trigger rolls or display results).

## Tech Stack

- **HTML/CSS/JavaScript**: For the frontend UI and logic, with a neumorphic design inspired by the provided style.
- **Node.js**: Handles dice roll simulations and probability calculations.

## How It Works
1. User clicks a "Roll" button to simulate a die roll.
2. The app randomly generates a number (1–6) and updates the frequency count for each number.
3. Experimental probabilities are calculated as:  
   `Probability = (Number of times a face appears) / (Total rolls)`.
4. Results are displayed in a user-friendly format, with optional code generation for Hammerspoon integration.

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/dice-probability-calculator.git# Experimental-Probability-Calculator

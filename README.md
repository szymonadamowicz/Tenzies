# Tenzies React App

## Overview
This is a simple React application called "Tenzies" that allows users to play a dice game. The goal of the game is to roll the dice until all dice show the same value. Players can click on each die to freeze its current value between rolls.

## How to Play
1. Click the dice to freeze or unfreeze them.
2. Roll the dice by clicking the "Roll" button.
3. Keep rolling until all dice show the same value.
4. If successful, the game will indicate "Tenzies," and you can start a new game.

## Tutorial
This app was created following a tutorial that you can find [here](#your-tutorial-link). The tutorial provides detailed steps and explanations for building the Tenzies React app.

## Components
- **App (App.js):**
  - Manages the state of the dice and the game.
  - Provides functions for generating new dice, rolling dice, and holding/unholding dice.
  - Uses the Die component to display individual dice.
  
- **Die (Die.js):**
  - Represents an individual die with its value and hold status.
  - Clicking on a die toggles its hold status.

## Dependencies
- **nanoid:** Used for generating unique IDs for each die.
  
## How to Run
1. Clone the repository.
2. Use the command `cd tenzies`.
3. Install dependencies using `npm install`.
4. Run the app with `npm start`.

## Code Structure
- **App.js:** Main application logic and state management.
- **Die.js:** Component for displaying individual dice.
- **index.js:** Entry point rendering the App component.
- **reportWebVitals.js:** Utilizes web-vitals library to report performance metrics.

## Acknowledgments
This app is a simple demonstration of React and state management for a dice game. Feel free to explore and modify the code to suit your needs. Enjoy playing Tenzies!

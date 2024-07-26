# Instructions for the 'Guess the Number' Project with JavaScript and React
Welcome to this project! You will create a simple number guessing game using JavaScript and React. Follow these detailed instructions to guide you through the process.

## Project Overview
You will build a web application where the user guesses a randomly generated number between 1 and 100. The game will provide feedback if the guess is too high, too low, or correct.

### Step 1: Project Setup
  
- Create a New React Application

- Open your terminal.
- Navigate to the directory where you want to create your project.
- Run npx create-react-app guess-the-number.
- Navigate into the project directory: cd guess-the-number.
- Clean Up Initial Setup:
    Remove unnecessary files and code created by default (such as App.test.js, logo.svg).
    Modify App.js to contain only a basic structure.
### Step 2: Application Structure
- Plan the State Variables:
- Think about the state variables you will need. You might need:
- A variable for the random target number.
- A variable for the user's guess.
- A variable for the message to the user (too high, too low, correct).
- A variable to track the number of attempts.
### Step 3: Implement the Game Logic
- Generate a Random Number:

- Create a function to generate a random number between 1 and 100.
- Set Up State in React:

- Use React's useState hook to manage the state variables.
- Create Input and Button Elements:

- Add an input field for the user to enter their guess.
- Add a button that the user can click to submit their guess.
- Handle User Input:

- reate a function to handle the logic when the user submits a guess.
This function should:
Check if the user's input is a valid number.
Compare the guess with the target number.
Update the message based on whether the guess is too high, too low, or correct.
Increment the number of attempts.
Display Feedback to the User:
Use a paragraph element or a similar HTML element to display messages to the user.

### Step 4: Additional Features
Reset Game Option:

Add a button that allows the user to restart the game.
This should reset all the state variables to their initial values.
Styling:
Apply basic styling to make the application visually appealing.

### Step 5: Testing
Test the Application:
Test the game to ensure all features work as expected.
Make sure edge cases are handled (e.g., non-numeric input, empty input).
Step 6: Optimization and Enhancements
Code Review:
Review your code to ensure it is clean and well-documented.
Look for opportunities to optimize your code.
Enhancements:

Consider adding new features such as:
Difficulty levels (easy, medium, hard with different ranges).
A counter that tracks the number of games played.
A leaderboard to store the best scores.
Good luck, and enjoy coding your 'Guess the Number' game! If you get stuck, try to debug by using console.log statements, and remember to consult the React documentation or other online resources.

# Number Guessing Game

This is a simple number guessing game built with React, TypeScript, Vite, and Tailwind CSS. The goal of the game is for the player to guess a randomly generated number within a certain range.

## Features

*   **User Input**: Players can enter their guesses.
*   **Game Messages**: Provides feedback to the player (e.g., "Too high", "Too low", "You won!").
*   **Game Statistics**: Tracks attempts, wins, and losses.
*   **Round History**: Displays a history of guesses for the current round.

## Workflow

1.  **Start Game**: Upon launching the application, a new game begins with a random number generated.
2.  **Make a Guess**: Enter a number into the input field and submit your guess.
3.  **Receive Feedback**: The game will provide immediate feedback, indicating if your guess was too high, too low, or correct.
4.  **Track Progress**: Your guess and the feedback are recorded in the round history. Game statistics (attempts, wins, losses) are updated.
5.  **Continue or Restart**:
    *   If the guess is incorrect, you can make another guess.
    *   If the guess is correct, you win the round. You can then choose to start a new game.

## Outcomes

*   **Win**: You guess the correct number within the allowed attempts.
*   **Lose**: You run out of allowed attempts without guessing the correct number.
*   **New Game**: After a win or loss, you have the option to start a fresh game, generating a new random number and resetting your attempts and history for the new round.



## Technologies Used

*   **React**: A JavaScript library for building user interfaces.
*   **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
*   **Vite**: A fast build tool that provides a lightning-fast development experience.
*   **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.

## Installation

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository_url>
    cd project
    ```
2.  **Install NPM packages:**
    ```bash
    npm install
    ```

## Running the Game

To run the game in development mode:

```bash
npm run dev
```

This will start a development server and open the game in your browser.

## Building for Production

To build the game for production:

```bash
npm run build
```

This will compile and optimize the project files into the `dist` directory, ready for deployment.

## Project Structure

*   `src/`: Contains the main application source code.
    *   `components/`: Reusable React components.
    *   `types/`: TypeScript type definitions.
    *   `utils/`: Utility functions, such as game logic.
*   `config/`: Configuration files for the project.
*   `public/`: Static assets.
*   `dist/`: Production build output.

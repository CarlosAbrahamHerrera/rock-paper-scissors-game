# Rock Paper Scissors Game

This is a simple Rock Paper Scissors game implemented using HTML, CSS, and JavaScript. The player can choose their move, and the computer randomly generates its move. The game determines the winner based on the classic Rock Paper Scissors rules and displays the result.

## Features

- Clean and modern UI with responsive design.
- Interactive buttons for player moves.
- Randomized computer moves using JavaScript.
- Displays game results with player and computer choices.

## File Structure

- `index.html`: Contains the structure and logic of the game.
- `assets/style.css`: Defines the styles for the game interface.

## How to Play

1. Open the `index.html` file in a web browser.
2. Click on one of the buttons (`Rock`, `Paper`, `Scissors`) to make your move.
3. The computer will randomly select its move.
4. An alert will display the result of the game, showing the moves and the winner.

## Code Overview

### HTML
- The HTML file includes a title, a container for the game, and buttons for user interaction.
- Each button calls the `playGame` function with the corresponding move.

### CSS
- The `style.css` file applies a modern dark theme with styling for the container, buttons, and hover/active states.
- Buttons change appearance on hover and click for a better user experience.

### JavaScript
- The `playGame` function handles game logic:
  - Compares the player's move with the computer's move.
  - Determines the winner and displays the result.
- The `pickComputerMove` function generates the computer's move randomly.

## Customization

- Modify the styles in `assets/style.css` to change the appearance.
- Add new features, such as:
  - A scoring system.
  - Persistent scores using local storage.
  - Animations for user interactions.

## Technologies Used

- **HTML**: Structure of the game.
- **CSS**: Styling for the UI.
- **JavaScript**: Game logic and interactivity.

## Compatibility

This game works on all modern web browsers that support HTML5, CSS3, and JavaScript.

## License

This project is open-source and available under the MIT License. Feel free to modify and use it as per your needs.

---

Enjoy playing Rock Paper Scissors!
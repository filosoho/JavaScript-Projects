# Pig Game 🎲🐷

Pig Game is a simple, interactive dice game built with JavaScript, HTML and CSS. The objective is for players to take turns rolling a dice and accumulating points, aiming to reach a predetermined score without rolling a "1", which resets their turn score. This project demonstrates core JavaScript concepts such as event handling, DOM manipulation and state management.

## Deployed Version

You can access the deployed version of the app here: [Pig Game](https://dicepig-game.netlify.app/)

## Features

- **Interactive Gameplay**: Real-time score updates and dice roll animations.
- **Player vs. Player Mode**: Two players take turns rolling the dice and accumulating scores.
- **Dynamic UI**: Updates to scores, current player and dice face displayed based on game events.
- **End Game Notification**: Announces the winner and allows for easy game resets.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies Used

- **HTML5**: Structure and layout of the game.
- **CSS3**: Styling and layout adjustments.
- **JavaScript (ES6+)**: Core game logic, event handling, DOM manipulation and animations.
- **Netlify**: Deployment for online access with continuous integration.

## Game Rules

1. The game has two players, taking turns to roll the dice.
2. **Roll Dice**:
   - If a player rolls any number other than 1, it is added to their **current score**.
   - If they roll a 1, their turn ends and their **current score** resets to 0.
3. **Hold**:
   - A player can choose to "hold," adding their **current score** to their **total score**.
   - This ends their turn, passing control to the other player.
4. **Winning**:
   - The first player to reach or exceed the winning score (default is 100) is declared the winner.

## Getting Started

### Prerequisites

All you need to run the Pig Game locally is a modern web browser.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/filosoho/JavaScript-Projects.git
   ```

   ```bash
   cd JavaScript-Projects/PigGame
   ```

2. **Open index.html**:

   You can run the game by simply opening the index.html file in your browser.

## Usage

1. **Start the Game**: Open the app, and player 1 can start by clicking "Roll Dice."
2. **Roll Dice**: Each player takes turns to roll the dice by pressing the "Roll Dice" button.
3. **Hold Score**: Press "Hold" to save your current score to your total score and pass the turn to the other player.
4. **Reset Game**: Press "New Game" to reset all scores and start a new game.

## Contributing

Contributions are welcome! To contribute:

- Fork the repository.
- Create a new branch (feature/your-feature-name).
- Commit and push your changes.
- Submit a pull request describing the changes.

---

Enjoy playing Pig Game and may the dice be ever in your favor!

# Dice2

A simple two-player dice game built using Vanilla JavaScript, HTML, and CSS. The game allows two players to roll a dice and accumulate scores, and the first player to reach a score of 100 wins.

Features
Two-player gameplay: Players take turns rolling the dice.
Dice roll animation: The dice rolls are visualized with images.
Score tracking: Each player's current score and total score are tracked.
Win condition: The first player to reach or exceed 100 points wins the game.
Reset functionality: The game can be reset to start a new game.
Technologies Used
HTML: For structuring the page.
CSS: For styling the page and layout.
JavaScript: For handling game logic, user interactions, and dynamic content.

Game Rules
Each player takes turns to roll a dice.
The player can accumulate points for each roll, but if they roll a 1, their current turn score will be lost, and the turn switches to the other player.
The player can hold their points, adding the current score to their total score, and then the turn switches to the other player.
The first player to reach a score of 100 wins the game.
After a player wins, the game can be restarted.

Example Game Flow
Rolling the Dice: A random number (1-6) is generated and displayed as a dice image.
Current Score: If the dice roll is not 1, the rolled value is added to the current score of the player.
Hold: When the player holds, their current score is added to their total score.
Winning: The game ends when a player’s total score reaches 100.
Restart: Clicking the "New Game" button resets the game and starts a fresh round.

https://amaansiddiq.github.io/Dice2/

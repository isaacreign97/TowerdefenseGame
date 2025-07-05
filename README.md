Simple Tower Defense
📖 Overview
Welcome to Simple Tower Defense! This is a classic tower defense game built entirely with vanilla HTML, CSS, and JavaScript, running in a single file. The goal is to demonstrate core game development concepts like a main game loop, entity management, player interaction, and state handling without relying on any external libraries or frameworks.

The objective is simple: stop the enemies from reaching the end of the path by strategically placing defensive towers.

🎮 How to Play
Objective: Prevent enemies from crossing the map. You start with 10 HP. Each enemy that reaches the end of the path will reduce your HP by 1. The game is over when your HP reaches 0.

Placing Towers: To build a tower, simply click on any empty (non-path) tile on the map. Each tower costs 40 money.

Earning Money: You start with 100 money. You earn 15 money for each enemy your towers successfully destroy.

Starting a Wave: Click the "Start Wave" button to begin the attack. A wave consists of 10 enemies.

Winning a Wave: Once all enemies in a wave are defeated, the wave is cleared, and you receive a bonus of 25 money. You can then start the next wave when you are ready.

✨ Features
Self-Contained: The entire game runs in a single index.html file. No servers, dependencies, or build steps are required.

Real-Time Game Loop: Uses requestAnimationFrame for smooth, efficient rendering and game logic updates.

Interactive Canvas: The game board is rendered on an HTML <canvas> element, handling all player input for tower placement.

Simple Economy: Manage your money to build defenses and manage your HP to stay in the game.

Basic Enemy AI: Enemies follow a predefined path from start to finish.

Tower Targeting: Towers automatically detect and fire at the nearest enemy within their range.

🚀 How to Run
To play the game, download the index.html file and open it directly in any modern web browser such as Google Chrome, Firefox, or Microsoft Edge.

🛠 Future Improvements
This project serves as a strong foundation. Here are some of the planned improvements to turn it into a more full-featured game:

Tower Variety: Introduce new tower types, such as:

Splash Damage Cannons: To handle groups of enemies.

Slowing/Frost Towers: To control the flow of enemies.

Long-Range Snipers: For high-priority targets.

Enemy Variety: Add different enemies that challenge various strategies (e.g., fast but weak swarmers, slow but durable tanks).

Tower Upgrades: Allow players to spend money to upgrade the damage, range, or fire rate of existing towers.

Advanced Wave System: Create more complex, pre-designed waves with a mix of enemy types to create a dynamic difficulty curve.

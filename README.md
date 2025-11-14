🐍 Byte Serpent: A Classic, Responsive Snake Game

A fast-paced, modern implementation of the classic Snake game, built entirely using HTML5 Canvas and Vanilla JavaScript. The game features a dark-mode theme, smooth gameplay, local high score tracking, and is fully optimized for all devices, including mobile.

🚀 Key Features

Classic Gameplay Loop: Guide the snake to eat food and grow longer while avoiding self-collision or hitting the boundaries.

Dynamic Difficulty: The game speed automatically scales and increases as the player achieves higher scores.

Persistent High Score: Tracks your all-time "Best" score using the browser's localStorage to save progress between sessions.

Full Mobile Responsiveness: The layout shifts from side-by-side to stacked on smaller screens, and the canvas dynamically resizes (90vw) to fit perfectly on any phone resolution without causing scrollbars.

Dual Control Scheme: Supports keyboard input (Arrow Keys / WASD) for desktop and dedicated, touch-friendly directional buttons for mobile players.

Custom Modal: Uses a custom UI modal for dangerous actions (like "Reset All") instead of disruptive browser alerts/confirms.

🕹️ How to Play

Controls

Input Type

Action

Keys/Buttons

Keyboard

Move Up/Down/Left/Right

Arrow Keys (↑, ↓, ←, →) or WASD

Mobile

Move Up/Down/Left/Right

Dedicated on-screen directional controls

Start/Reset

Start game (from stopped or dead state)

Spacebar or the "Start" button

Objective

Score points by eating the red food. The game ends if the snake hits a wall or collides with its own body. Achieve a new high score to see the special Gold glow effect!

💻 Technology Stack

HTML5 Canvas: Used for drawing the game grid, snake segments, and food for efficient rendering.

Vanilla JavaScript: Handles all game logic, collision detection, game state management, and interaction listeners.

CSS3: Custom styles, Flexbox/Grid for layout, and media queries for responsiveness.

Local Storage: Used for basic persistent data storage (high score).

✨Acknowledgements

The final code was significantly improved and stabilized with the assistance of the Gemini AI model.

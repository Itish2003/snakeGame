<h1>Snake Game in C++ with SFML</h1>

<h2>Introduction</h2>
The "Snake Game" is a C++ project developed with the Simple and Fast
Multimedia Library (SFML). It presents a classic game where players control a
snake to consume food while avoiding self-collision and obstacles. The primary
aim is to grow the snake's length until a collision terminates the game.

<h2>Project Overview</h2>
<h3>Purpose</h3>
The project serves to demonstrate C++ game development using SFML,
emphasizing critical concepts such as game loops, collision detection, and user
input handling.

<h3>Features</h3>
• Four-directional snake movement.<br>
• Random food generation.<br>
• Collision detection with walls and the snake's own body.<br>
• Game over screen with animation.<br>
• Display of the food counter.

<h2>Project Components</h2>
The core of the project is the SnakeGame class.

<h2>Key Elements</h2>

• Member Variables: Game objects, textures, and state.<br>
• Initialization: Setting up the game, SFML library, including the snake and
food.<br>
• Game Loop: Managing game state and updates.<br>
• Event Handling: Capturing user input.<br>
• Collision Detection: Identifying snake collisions.<br>
• Food Interaction: Handling food consumption.<br>
• Generation: Random placement of food and walls.<br>
• Rendering: Drawing game elements.

<h2>Challenges Faced During Development</h2>
• Challenges included the initial overlapping spawn positions of the snake,
food, and walls.<br>
• Solution: Implementation of a finite loop to ensure a safe spawn
distance from the snake, by resetting the spawn location until the
elements no longer overlap.

<h2>Conclusion</h2>
The Snake Game project provides a foundation for C++ game development
with SFML, offering insights into fundamental game mechanics and practical
C++ coding using an external game library-such as SFML.

<h2>Acknowledgments</h2>
Acknowledgments are extended to the following-<br>
• SFML official documentation<br>
• SFML library<br>
• YouTube tutorials on game development<br>
• ChatGPT for guidance and understanding the errors

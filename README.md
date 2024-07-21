```Snake Game in C++ with SFML```

1. Introduction
The "Snake Game" is a C++ project developed with the Simple and Fast
Multimedia Library (SFML). It presents a classic game where players control a
snake to consume food while avoiding self-collision and obstacles. The primary
aim is to grow the snake's length until a collision terminates the game.

2. Project Overview
2.1. Purpose
The project serves to demonstrate C++ game development using SFML,
emphasizing critical concepts such as game loops, collision detection, and user
input handling.

2.2. Features
• Four-directional snake movement.
• Random food generation.
• Collision detection with walls and the snake's own body.
• Game over screen with animation.
• Display of the food counter.

2.3. Project Components
The core of the project is the SnakeGame class.

3. Key Elements

• Member Variables: Game objects, textures, and state.
• Initialization: Setting up the game, SFML library, including the snake and
food.
• Game Loop: Managing game state and updates.
• Event Handling: Capturing user input.
• Collision Detection: Identifying snake collisions.
• Food Interaction: Handling food consumption.
• Generation: Random placement of food and walls.
• Rendering: Drawing game elements.

4. Challenges Faced During Development
• Challenges included the initial overlapping spawn positions of the snake,
food, and walls.
• Solution: Implementation of a finite loop to ensure a safe spawn
distance from the snake, by resetting the spawn location until the
elements no longer overlap.

5. Conclusion
The Snake Game project provides a foundation for C++ game development
with SFML, offering insights into fundamental game mechanics and practical
C++ coding using an external game library-such as SFML.

6. Acknowledgments
Acknowledgments are extended to the following-
• SFML official documentation
• SFML library
• YouTube tutorials on game development
• ChatGPT for guidance and understanding the errors

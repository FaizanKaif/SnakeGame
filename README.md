# SnakeGame

This is a fun game where you control a snake and try to eat fruits. The more fruits you eat, the higher your score.

How to Play:
Use the arrow keys on your keyboard to move the snake.
Try to guide the snake to eat the fruits that appear on the screen.
Each time the snake eats a fruit, your score goes up.

**Python:** Python is a programming language used to write the code for this game. It's known for its simplicity and readability, which makes it great for beginners and experienced programmers alike.

**Pygame Library:** Pygame is a set of Python modules designed for writing video games. It provides functionalities for handling graphics, sounds, and user input. In this game, Pygame helps to create the game window, draw shapes (like the snake and fruits), and manage user interactions (like keyboard input).

**Game Logic:**
•	The game window is created with a size of 720 pixels wide and 480 pixels tall.
•	The snake moves around the screen in blocks of 10x10 pixels.
•	Fruits randomly spawn on the screen, and the snake's goal is to eat them.
•	When the snake eats a fruit, its length increases, and the player's score goes up.
•	If the snake hits the walls or itself, the game ends.
•	The game keeps track of the score and displays it on the screen.

**Game Loop:**
•	The game runs in a continuous loop, where it constantly checks for user input, updates the game state, and redraws the screen.
•	It uses a clock to control the speed of the game, ensuring it runs smoothly.

**Snake Movement:**
•	The snake's movement is controlled by the arrow keys on the keyboard.
•	Each time a key is pressed, the snake's direction changes accordingly.
•	The snake's position is updated based on its current direction, and its body grows when it eats a fruit.

**Collision Detection:**
•	The game checks for collisions between the snake and the walls, between the snake and itself, and between the snake and the fruits.
•	If a collision occurs with the walls or itself, the game ends.
•	If the snake eats a fruit, its length increases, and a new fruit spawns at a random location.

**Scoring:**
•	The player's score increases by 10 points each time the snake eats a fruit.
•	The score is displayed on the screen for the player to see.

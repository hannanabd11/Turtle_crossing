# Turtle_crossing

Turtle Crossing Game (Frogger Clone)
This is a simple arcade-style game built using Python's  module. The player controls a turtle that must cross a busy road filled with moving cars. Each successful crossing increases the difficulty level!



 How to Play
• 	Objective: Help the turtle cross the road without getting hit by a car.
• 	Controls: Press the Up Arrow key to move the turtle forward.
• 	Scoring:
• 	Each time you reach the top of the screen, you level up.
• 	With each level, cars move faster, increasing the challenge.
• 	Game Over: If the turtle collides with a car (distance < 20 units), the game ends.

 Game Logic Summary
• 	The game loop runs continuously, updating the screen every 0.1 seconds.
• 	Cars are randomly generated and move from right to left.
• 	Collision detection checks if any car is too close to the turtle.
• 	The scoreboard updates the level each time the player reaches the finish line.


🛠 Requirements
• 	Python 3.x
• 	No external libraries required — uses built-in  and  modules.

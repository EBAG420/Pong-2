

Part 1. Unit Testing the Game Mechanics
Description:
Pong is a game meant to be played by 2 players where you use 2 paddles to hit a ball and try to hit it into the other side
Action:

	•	Movement can move your paddles up and down
	•	Collision detection game detects when the paddle hits the ball
w,s or arrow keys to move


Part 2. Logic Testing the Game Rules and Calculations

The game ends when one player reaches a score of 100

Action::
	•	Score calculations every time one person makes a goal they get one point 


Part 3. Boundary Testing: Edge Cases and Limits

The game is played on the screen and the walls have collision and if the ball goes past the paddles they reset to their original position

Action:
•	Maximum score if they gain 100 they win the game
•	Minimum score the score can not go below 0
•	Maximum balls when multiple balls ar in play the game still runs very well



Part 4. Integration Testing: System Interaction

The collision of the walls and the paddles + the scoreboard work as intended
Action:
	•	Gameplay and scoring after every goal you get one point
	•	Movement and collision you can move the paddles into different positions



Part 5. Handling Bad Input and Run-Time Errors

Action:

	•	Invalid user input nothing will happen
	•	Unexpected game states you'll have to reset the game
	•	Error handling no it does not






Part 6: test information


1. Player count: 
2 players
2. Game will start and expect you to have another player
3. Score increase 
1	
4. You gain 1 point for every goal
5. Invalid input:
“bc”, “#@!”, 'return key' 
Game will ignore all key presses except w,s,up arrow key, and down arrow key
6. Menu selected
select if you want to go against ai or player



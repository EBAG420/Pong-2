Test Plan Frame for Your Game

Part 1. Unit Testing the Game Mechanics
Description:
Pong is a game meant to be played by 2 players where you use 2 paddles to hit a ball and try to hit it into the other side
Action:
A) Brainstorm the basic mechanics in your game. Consider aspects like:
	•	Movement can move your paddles up and down
	•	Collision detection game detects when the paddle hits the ball
B) w,s or arrow keys to move


Part 2. Logic Testing the Game Rules and Calculations
Description:
The game ends when one player reaches a score of 100

Action::
	•	Score calculations every time one person makes a goal they get one point 


Part 3. Boundary Testing: Edge Cases and Limits
Description:
The game is played on the screen and the walls have collision and if the ball goes past the paddles they reset to their original position

Action:
A) Think about situations where the game might behave unusually. List normal game play and 'special', extreme or rare situations.  Here are some ideas to get you started:
•	Maximum score if they gain 100 they win the game
•	Minimum score the score can not go below 0
•	Maximum balls when multiple balls ar in play the game still runs very well



Part 4. Integration Testing: System Interaction
Description:
The collision of the walls and the paddles + the scoreboard work as intended
Action:
	•	Gameplay and scoring after every goal you get one point
	•	Movement and collision you can move the paddles into different positions



Part 5. Handling Bad Input and Run-Time Errors
Description:
When testing for bad input or run-time errors, the goal is to ensure that the game can handle unexpected or incorrect input without crashing or behaving unpredictably. This also includes handling errors that could occur during game saving/loading, unexpected game states (like getting stuck in an infinite loop), or interactions with external systems (e.g., online features or databases, if applicable).


Action:

	•	Invalid user input nothing will happen
	•	Unexpected game states you'll have to reset the game
	•	Error handling no it does not






Part 6: Build a table to present all the test information
Once you have identified the various tests, use a table to organize and present your test cases. The table should include the following columns:
**Test Case**: A brief description of what is being tested
**Test Data**: The input or condition being tested
**Expected Outcome**: What you expect to happen when the test is executed


Test Case
Test Data
Expected Outcome
Player count
2 players
Game will start and expect you to have another player
Score increase
1	
You gain 1 point for every goal
Invalid input
“bc”, “#@!”, 'return key'
Game will ignore all key presses except w,s,up arrow key, and down arrow key
Menu selected
There is no menu
There is no menu


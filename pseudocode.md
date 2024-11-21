Pong
1. Initialize Game
Initialize game window and assets.
Set up paddles for Player 1 and Player 2.
Initialize the first ball with its position and velocity.
Set up a counter to track turns or score.
Create an empty list to store all active balls.
2. Main Game Loop
While the game is running:
Handle Input:
Capture player input for paddle movements.
Quit the game if the quit event is triggered.
Update Game State:
Move all active balls based on their velocities.
Check for collisions:
If a ball hits a paddle, reflect it.
If a ball hits the top or bottom wall, reverse its vertical direction.
If a ball crosses the left or right boundary:
Increment the score for the opposite player.
Reset the ball position and velocity.
Track the number of turns or score milestones.
Add a New Ball:
If the counter reaches a threshold (e.g., every 5 turns or goals):
Create a new ball with a random direction and velocity.
Add the new ball to the list of active balls.
Draw Game Objects:
Clear the screen.
Draw paddles, all active balls, and scores.
Update the game window.
Delay for Frame Rate Control:
Wait for a short period to control the frame rate.
3. End Game:
Display "Game Over" or final scores.
Clean up resources and close the game.
4. Key variables
 paddle1, paddle2: Represent the positions of the two paddles.
balls: A list of all active balls, where each ball has position and velocity.
turn_counter: A counter to track when to add new balls.
score1, score2: Scores for Player 1 and Player 2.

# Pong-game

# Description
This program uses java code to create the game pong. Using java swing to create the screen of the game. Using java awt to create the graphics which are displayed on the screen. It is composed of 6 classes which are the Main, Panel, Frame, Paddle, Ball, Score. The Main class stores the main method that runs the program. The Frame class sets the parameters of the frame of the panel inside of the instructor. The Paddle class creates the constructor for the paddle objects it also, takes the key events to move the paddle up and down the screen and the graphics which set the color and the size of the paddles. The Ball class creates the constructor for the ball objects it also creates the movement of the ball which moves in random directions it also set the graphics like the paddle. The Score class creates the contructor which takes both players and displays the score and the graphics which is the same as the paddle and ball. Then last the Panel class which creates all the variables for the screen, ball, and paddle size. It creates the objects for image, graphics, thread, random, paddles, ball, and score. Then the panel constructor set the things stored on the screen. Then the newPaddles and Ball methods set the parameters of the objects. Then the same with the graphics plus paint which fills the frame. The checkCollisions methods checks the collisions of each object one for the ball hitting the side of the wall, one for the ball hitting the paddles and each time it hit the paddle it increases velocity. Also, it checks the collision of the top and bottom of the paddle and make sure that it doesn’t go past the frames height and width parameters. It has the run method which is the runtime for the game which sets the frame per second that the game runs at. That is what makes the pong game run.

# How to Run
1. Download the zip file
2. Unzip the file
3. Use a IDE that runs on java
4. Open the unziped file inside of that IDE

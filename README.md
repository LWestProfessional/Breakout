A version of Breakout that I created by folowing the Tutorial provided to me. The Paddle is controlled by the mouse and the player has three lives. If the Ball touches the bottom of the screen you will lose a life and once all lives are expended the game will reset. The Ball can destroy the Bricks in the upper half of the screen and if you can keep it bouncing long enough to destroy every block you will win and recieve a congratulatory message. After the message has been closed the game will reset.
The function mouseMoveHandler allows the user to move the Paddle with their mouse cursor, this overrides the two keydown functions so disabling it is necessary for keyboard play.
The collisionDetection function causes the Ball to invert its movement on the axis perpendicular to the surface it has hit.
The drawBall function draws the Ball on the canvas.
The drawPaddle function draws the Paddle on the canvas.
The drawBricks function draws an array of bricks on the canvas.
The drawScore function draws a score counter on the canvas.
The drawLives function draws a life counter on the canvas.
The draw function clears the canvas and calls every other function every frame, handles the life losing mechanic, and resets the location of the Ball and Paddle after each life is lost.

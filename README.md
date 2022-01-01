# Brick-Breaker

# Intorduction 
This project is a game called Brick Breaker. We all played this game somehow.
I have used OpenGL with CPP in order to complete the project. And I have used CodeBlocks Application in order to write the code.

# How the Game Works
Now, there will be a cube, a block at the bottom of the screen, and total number of 45 bricks. The cube will go up and down, and try to hit the one of the bricks, if it becomes successful in doing so the brick that was hit will be removed. The game will continue until the cube misses the block at the bottom after hitting a brick or after going downward, or it hits all of the bricks one by one. 

# Functions
I have taken following functons in order to complete the project.
- void initialize();	//To set the initial co-ordinates of the objects on the screen
- bool check_collision(float, float, float, float, float, float, float, float); //Function for checking collision
- void draw();		//Render the objects on the screen using the latest updated co-ordinates
- void reshape();		//Modify the co-ordinates according to the key-presses and collisions etc...
- void specialUp(int,int, int); //Checks for Key Press
- void specialDown(int, int, int); //Checks for Key Release
- void revert();

# Screenshot
  ![Brick Breaker](https://user-images.githubusercontent.com/76622051/147859018-50d75822-bc10-49ee-862e-f6a7be322980.PNG)

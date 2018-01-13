# Final Project - "Flappy Shape - Shanghai Edition"

This is a final project I did freshman year for Interaction Lab, a core class for the major Interactive Media Arts at NYU Shanghai. 

This is my first time working with any programming languange, please bear with my messy coding. Me and my project partner decided to do a game very similar to flappy bird. Using Processing and Arduino, the goal of the game is to survive as long as possible by not navigating around clouds and buildings. The game is controlled by an Arduino Force Sensitive Resistor, which we placed under a mat so that the player is controlled by stepping/jumping motions.

Our goals for this project were :

* Active interaction: Initally starting out with a vibration sensor, we realized a Force Sensitive Resistor (FSR) sensor allowed for much more interaction between players and the game. People needed to use their whole body instead of just using their thumb to press the sensor.

* Collision Detection: Throughout the project, we struggled to align the sensor exactly with the borders of the objects in the game so that it would detect when the player hit an object.  Collision detection was difficult since we had different building heights, which meant a collision detection would have to be called for each building. While we initally started by calling each dimension of a building, we were able to fix the problem by creating an array of buildings with randomized heights. 

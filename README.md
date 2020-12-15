# The Mars Rover Kata

You are exploring Mars by sending a remotely controlled vehicle to the red planet. 

Here is the API that moves a rover around a grid
With this API you can translate the commands to instructions that the rover receives.


The program starts with a rover on a 10x10 grid which accepts 3 arguments: 
  X Position 
  Y Position 
  Initial Direction the rover faces

You can move your rover by calling the commands method. 
Commands accepted: 
  'F' moves the rover forward by one space
  'B' moves it backward by one space
  'N', 'E', 'S' and 'W' turns it to the north, east, south and west, respectively. 
  
  
Through the rover's travelLog property you will see the path traveled by the rover. This property accumulates all attempted movements and is logged after each command character.

And watch out! the grid is filled with several obstacles!
  

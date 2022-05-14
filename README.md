# Mechatronics-ME588
This repository contains the code and assets for the capstone project for the course Mechatronics - ME 588 at Purdue University.

The aim of this project was to build an autonomous robot to compete in the game of "whack-a-mole". It must autonomously navigate on a 8ft x 8ft game field made of 16 square tiles–five blue tiles, five red tiles, five yellow tiles, and a single white starting tile. The robot must drop foam cubes onto the 2ft x 2ft coloured tile based on user input and return to the starting point. The robot must come to a complete halt after two minutes of playing regardless of whether the robot was able to drop all the cubes.

The robot consistently and precicely completed all the major objectives outlined above in approximately fifty-five seconds which led the team to be placed second in the course-wide competition. 

For future work, there is room for improvement in making the robot achieve its objectives faster. For example, currently, the robot comes to a complete stop on every square tile to detect its color. Going forward, the robot could be programmed to detect the color of the square tiles as it moves across each tile and comes to a stop once it detects the desired color. It might also be desired to  include  an  error-correcting  state.  Currently, the  robot moves  on  a  predetermined  path; if  it is thrown off course, it will not find its path and complete the game. An error correcting state could implement gyroscopes and ultrasonic sensors to help the robot better locate itself and correct its path to finish the game if any extraneous disturbances occur on the path of the robot.


# Team Members:
1. Arijeet Nath
2. Colin Feustel
3. Norawish Lohitnavy
4. Yoo Hyun Kim
5. Cheng Kong

# FSM State Transition diagram
![image](https://user-images.githubusercontent.com/94764537/168403170-c64275ca-bec9-412b-a235-75236144847d.png=250x250)


# Video of the robot navigating the arena
https://user-images.githubusercontent.com/94764537/168402349-5cb47798-b490-41eb-8536-912cad8ffef6.mp4




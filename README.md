# Line-following-robot  
EEE3099S: Mechatronic Design  
Completed: November 2021  
Project Partner: SHKMOH25  

Files Included:
1. JFTCRY001_SHKMOH025_EEE3099S_Milestone4.pdf: Project report
2. Maze Solver Project Brief: Project instructions
3. matlab-files.zip: MATLAB files
4. robot.jpg: image of maze solving robot


The aim of this project was to develop an autonomous mobile robot to participate in a maze solving operation. A self-powered differential drive robot was provided and  Matlab and Simulink were used to implement both a simulation and a hardware solution. There were two phases to this project. The first phase was the learning of a simple maze, where the robot needed to follow a black track with a width of 18mm to learn the maze and find the shortest path from the beginning to the end. The robot was required to start at the push of an accessible button and indicate its mode of operation with an LED. The robot had to then stop and indicate on the LED once it had learnt the maze. The robot needed to be prompted to optimise the path and indicate with a blinking LED that it can solve the maze using the optimised path once it is ready. This leads to the second phase which was a timed event where the robot was required to travel through the same maze on the shortest path from the beginning to the end of the maze, where the end of the maze was indicated by a solid black box. The first part of the solution was to design a motion control algorithm which allowed the robot to move forward in a straight line as well as rotate about its centre. The second part of the solution was to design a line sensing algorithm and a line configuration algorithm to sense the line of the maze and 8 different configurations. And finally, the third part of the solution was to implement an algorithm that made use of the previous solutions to learn the maze and race through the shortest path.

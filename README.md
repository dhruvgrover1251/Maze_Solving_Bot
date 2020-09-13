# Maze_Solving_Bot
This repository consists of small documentation of making a maze solving bot.

## What is maze solving bot?
A maze is a complicated system of paths from entrance to exit. Maze solving problem involves determining the path of a mobile robot from its initial position to its destination while travelling through environment consisting of obstacles. In addition, the robot must follow the best possible path among various possible paths present in the maze.<br>

Autonomous maze solving robot that we have built first goes from start to end searching in the maze using wall follower algorithm (left hand rule) and then processes out the shortest possible path by eliminating dead ends and takes that path next time . It does all of that without any human assistance.

## What is wall following algorithm?

The most common algorithm for maze solving robot is Wall following algorithm. The robot will take its direction by following either left or right wall. This algorithm also called, left hand-right hand rules. Whenever the robot reaches a junction, it will sense for the opening walls and select it direction giving the priority to the selected wall. By taking the walls as guide, this strategy is capable to make the robot reaches the finish point of the maze without actually solving it. <br>

![algo table](https://github.com/dhruvgrover1251/Maze_Solving_Bot/blob/master/algotable.PNG)  <br>

#### Here is the flow chart of algoritm

![algo table](https://github.com/dhruvgrover1251/Maze_Solving_Bot/blob/master/algotable.PNG)  <br>

 Here is the flow chart for algoritm <br>
 
 ![algo table](https://github.com/dhruvgrover1251/Maze_Solving_Bot/blob/master/flow_chart_algo.PNG)  <br>
 
 ## Components required:
1. Arduino UNO board
2. Motor driver
3. 2 DC motors
4. Bread board
5. 3 ultrasonic sensors
6. 2 9V battery
7. Chassis
8. 2 tires and ball caster
9. Jumpers
 
 For code check the code file.

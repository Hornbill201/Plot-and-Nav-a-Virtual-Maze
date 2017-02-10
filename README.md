# Plot-and-Nav-a-Virtual-Maze
## Udacity Capstone Projects: Plot and Navigate a Virtual Maze

## How to run the code
In order to run the tester.py script, type the following command in the terminal:

```
python tester.py test_maze_01.txt ff no
```

There are five arguments. 

* The first one is ``python'' command. 
* The second one is the ``tester.py'' script. 
* The third one is the file name of the maze we want to test. There are three maze provided by Udacity, which are ``test\_maze\_01.txt'', ``test\_maze\_02.txt'', and ``test\_maze\_03.txt''. Later, I will add another test maze ``test\_maze\_04.txt'' which is generated by myself. 
* The fourth argument is the algorithm we want to use. There are three algorithms can be chosen: ``rf'' stands for the Right-First algorithm; ``nf'' stands for the New-First Algorithm; ``ff'' stands for the ``Flood-Fill'' algorithm. 
* The fifth argument can be ``yes'' or ``no'', which indicate whether the robot is set to keep exploring new cells after reaching the center and on the way back to the origin. 


### Implementation

The implementation consists of four different classes: algorithms, cell, robot, training. 

* Algorithms: has the logic that enables the robot to decide how to move.
* Cell: represents a square cell in the maze.
* Training: representation of the maze from the robot’s view.
* Robot: control the robot to move around the maze.


#### Requirements

Python 2.7.X

Numpy
# proj2_michael_titus
BFS Path Planning with Obstacles

Open and run BFS_point.py

Input the starting and finishing coordinates.

Program will check all surrounding coordinates of the starting coordinates (this is the first parent node). All valid coordinates (coordinates that do not interfere with the obstacles and have not yet been travelled to) are saved to be future parent nodes. Program outputs current parent nodes being checked to show progress. At end, program outputs map, showing obstacles in black, travelled locations in gray, and the most optimal path as a black line through the gray travelled points. Program also outputs the total distance travelled for most optimal path from start to end goal.

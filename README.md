# proj2_michael_titus
BFS Path Planning with Obstacles

Open and run BFS_point.py

Input the starting and finishing coordinates.

Program will check all surrounding coordinates of the starting coordinates (this is the first parent node). All valid coordinates (coordinates that do not interfere with the obstacles and have not yet been travelled to) are saved to be future parent nodes. Program outputs current parent nodes being checked to show progress. At end, program outputs map, showing obstacles in black, travelled locations in gray, and the most optimal path as a black line through the gray travelled points. Program also outputs the total distance travelled for most optimal path from start to end goal.

proj2_michael_titus_examples.mp4 shows short video of program at work, with start at (70,20) and end at (150,30)

proj2_michael_titus_complex.png shows example output of program for a more complex path, starting at (75,30) and ending at (354,220). This output took 20 minutes+ to run.

# Monty-Hall-Simulation

Creating simulation to understand the monty hall problem. The simulation works similar the game show, but here we consider both the cases in the same simulation - sticking to the door and switching to a new one.

PROCEDURE
For each simulation run
1) We make a selection and make note of this (original) selection
2) Now, we check the other two doors and select the one which doesn't have a Goat (no prize)
3) If both of them have Goat (which should be for 33% of the cases), we randomly pick one
4) Now we have the new door (switched door) as well
5) We check the probability of winning for the old selection and new selection. 

As we run more number of simulation we see that the probability of winning for sticking with the old door is 33% and 66% for switching to a new door

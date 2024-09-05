# Boolean Satisfiability Problem
Solving Random 3-SAT(Boolean satisfiability problem) using Evolutionary algorithms like Genetic Algorithm and Simulated Annealing.

# Simulated Annealing
Due to the flowchart, we randomly get an instruction and add to it some noise. if the temp function is greater than our original function, then change the original variable to the temp and check the termination condition. if the temp function is less than our original function, then we check our exponential function with a random number that is generated. it is like a second chance. 
<p align="center">
<img src="https://github.com/user-attachments/assets/4f0e34ef-bf41-41f5-8d80-147918cd400a" height="400">
</p>

# Generic Algorithm
You can see how the cross-over, mutation, parent choice, and making children procedures are implemented.




# DataSet
You can access the data set with this [Link](https://drive.google.com/file/d/1xnXeA9t6GqsySeu5G3Bz8MYZDEAWG7iM/view).


The Dataset is a .cnf file and in the first row has two numbers n and m.
- n is the number of variables and m is the number of instructions.
- In the next m rows, each row contains an instruction for three variables.
- The negative form of each variable is shown with a hyphen(-).
- we use ```OR``` operation between each variable and use ```AND``` operation between each row.

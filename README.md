# AIcourse21_Exercises
I had an AI course in the first semester of my third year at the University of Kashan, it was about solving problems with Uninformed and Informed Searching Strategies, Local Searches Algorithms, Genetic Algorithms, Adversarial Search, and Constraint Satisfaction Problems.

I had three exercises about implementation Breadth First Search Algorithm, Iterative Deepening Depth First Search, A* Search, and Simulated Annealing. In the following you can see exercises:

## Exercise 1:
 **A)** Implement **_Breadth First Search Algorithm_** for routing in the following maze.

 **B)** Implement **_Iterative Deepening Depth First Search Algorithm_** for routing in the following maze.

## Exercise 2:
Implement A* Search Algorithm for routing in the following maze. 

![gitMaze](https://user-images.githubusercontent.com/66471227/149549172-8005a1b8-3d9d-45c7-9a14-9ee767bab435.PNG)

## Exercise 3:
Assume you want to select **20** locations to build **20** branches of a chain store, according to the table(A) you have distance between stores, also wares should move between branches, you can see the cost of moving wares between branches in table(B), you should choose a place for each branch in a way that total costs lead to minimum cost.

The above problem can be modeled as an optimization problem as follows:

![formula](https://user-images.githubusercontent.com/66471227/149549481-28c00d64-3cdf-4b85-8338-1009d9a385b1.PNG)

Where **_X(i,j)_** is equal to one if branch **j** is assigned to location **i**, **_D(i,k)_** is equal to distance between location **i** and location **k**, **_W(j,s)_** is equal to the cost of moving wares between branch **j** and branch **s**, and **_n_** is equal to **20**.

Solve the above problem by using **_Simulated Annealing_** Algorithm with at least **150** epoch.






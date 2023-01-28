# nyuhw
Doodlebug and Ant Simulation

This is a program that simulates the behavior of doodlebugs and ants in a 20x20 grid. The program initializes an array of objects called "orgObjs" with all elements set to NULL. It then creates arrays for each type of object: "EmptyArray" for empty spaces, "objDoodles" for doodlebugs, and "objAnts" for ants. The program then randomly generates 5 doodlebugs and 100 ants and places them on the "orgObjs" array in random locations. Any remaining empty spaces in the array are filled with objects from the "EmptyArray". The program then prints the initial state of the grid and waits for the user to press enter to initiate the next time step. The function "simulateOneStep" is called each time the user presses enter and updates the state of the grid based on the behavior of the doodlebugs and ants.
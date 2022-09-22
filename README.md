![Alt text](https://upload.wikimedia.org/wikipedia/commons/3/3d/ISAE_SUPAERO_72_cmjn.png)
# Applied Aerodynamics
This repository contains a selection of codes, scripts and other materials developed by students taking the Applied Aerodynamics module at ISAE-SUPAERO. 

## Year 2021-2022

# Aerofoil optimisation by means of genetic algorithm
Authors: A. Zigante, E. Foglia, A. Schioppa

## Structure and functionalities
The proposed genetic optimization algorithm works by merging airfoils drawn from a library of candidate shapes.\ The merging is carried out using the INTE function of Xfoil, that is also used to evaluate the performances of the parameters.\
Hereafter a summary of the functionalities of the parts of the algorithm, to facilitate its use:
1. algorithm.py: is the centre of the program. Imports the othes modules and runs the optimization routine;
2. PYfoil.py: contains the dedicated function to run Xfoil and plot polars and boundary layer solutions;
3. obj_fun.py: encode the objective function to be maximized.

As inputs the program requires a library of candidate shapes, to be stored in a folder named 'library' in the same folder as the project. A folder for the resulting airfoils called 'generation' and one for the computed perfomances called 'data' are also required.\

As output the program provides the best airfoil. A file called 'out.txt' allows to check the behaviour of the algorithm (has been particularly useful for bug detection and correction).
As inputs the program requires a library of candidate shapes, to be stored in a folder named 'library' in the same folder as the project. A folder for the resulting airfoils called 'generation' and one for the computed perfomances called 'data' are also required. In oreder to print the results compared to a selection of other airfoils, a folder called 'reference_data' contains the respective polars, calculated previously.

As output the program provides the best airfoil. A file called 'out.txt' allows to check the behaviour of the algorithm (has been particularly useful for bug detection and correction).



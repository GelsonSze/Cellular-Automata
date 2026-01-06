# Cellular-Automata

This code displays the step by step formation of an elementary cellular automata in a gif file.

## ELEMENTARY CELLULAR AUTOMATA

An elementary cellular automata is a one dimensional cellular automaton where each cell only has two states (0 or 1). With this, the cells depend on the values of their immediate neighboring cells. Given this, we could say that there are 8 possible scenarios/states that a cell could be in. Such states are the following: 000, 001, 010, 011, 100, 101, 110, 111. Since there are 8 possible states that each cell could be in, each state also has its own mapping or rule, such that it determines the value of the cell on the next step. Furthermore, since the mapped values may only be either 0 or 1, there are 256 (2^8) possible combinations of rulesets such that each number between 0 to 255 can be represented as an 8-bit binary number wherein each bit represents the determined resulting value of the cell in the 8 aforementioned scenarios.

## PROGRAM

The program of the elementary cellular automata is placed in a jupyter notebook. The notebook can be found in the repository and it is named as ElementaryCA.ipynb. The program uses rule 30 of the elementary cellular automata as default. Note that the rule number can be changed so long as it is within 0 to 255. 

**Do keep in mind that running the program would generate a gif file showing the animation of the elementary cellular automata.**

## ANIMATION

After initializing the figure to be displayed, FuncAnimation from matplotlib was utilized for the overall animation, showing a step-by-step (row-by-row) formation of the elementary cellular automata. The figure is also stored in a gif file to continuously show the process. Additionally, imshow from matplotlib was also used to display an image with our names composed of a 2-dimensional numpy array. 

### Sources:
Ilevski, V. (2021, May 1). Cellular Automata [Source Code]. https://github.com/IlievskiV/Amusive-Blogging-N-Coding/blob/master/Cellular%20Automata/cellular_automata.ipynb

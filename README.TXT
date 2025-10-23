Project: automaton
Aothors: David J. Barnes and Michael Kölling

This project is part of the material of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 7.

Lab III
26. The amount of * outputted increases each time I call step(). When I call run() and input 
numSteps (7), The code will print * 7 times including the increase.
27. Even after clearing the terminal window, calling step() or run() continues the pattern from 
the before clearing.
28. Based on all the fill() variants, it contains two values. It seems that the first value 
is assigned to the second value.
29. By altering state[numberOfCells / 2] = 1; to state[numberOfCells / 2] = 2;, The first state 
now has 3 *. No matter how many times I reset, the same pattern will emerge as long as it has 
the same value.
30. x
31. If I replace nextState with state, and then call either reset() or update(), calling 
print() will print nothing. I think this is because another variable must store the newly 
updated data, so you can't reuse state since it contains the previous data.
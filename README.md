### First assignment for **Intelligent Systems** course, UL FRI 2021/22
- *Lecturer:* prof. dr. Marko Robnik Šikonja
- *Assistants:* Blaž Škrlj, Tadej Škvorc

*The assignment was done in collaboration with Bernard Sovdat.*

# **Genetic algorithms** in R

We had to use genetic algorithms to solve a mathematical game using R and GA library.

- [instructions](instructions.pdf)
- [code](assignment1.rmd)
- [report](report.pdf)


### Summary:
The goal of the first seminar assignment is to solve a mathematical game using genetic algorithms. You are given a set of numbers and a set of mathematical operators and a target number, and then have to arrange the numbers and operators in an equation to get as close to the target number as possible. 

There are three tasks to be completed: 
1. represent the solutions in a format compatible with the R GA library, 
2. implement a fitness function to optimize the problem, and 
3. write custom crossover and mutation functions that generate valid equations. The crossover and mutation functions should be based on existing GA library functions and should return valid equations. 

Finally, test the genetic algorithm using different parameters and present the results.
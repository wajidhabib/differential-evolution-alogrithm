# The Implementation of Differential Evolution in Python

In evolutionary computation, differential evolution (DE) is a method that optimizes a problem by iteratively trying to improve a candidate solution with regard to a given measure of quality. Such methods are commonly known as metaheuristics as they make few or no assumptions about the problem being optimized and can search very large spaces of candidate solutions. However, metaheuristics such as DE do not guarantee an optimal solution is ever found.

The basic structure of differential evolution can be summed up below:
```
1) Initialize a random population of individuals throughout the search space.
2) while iter <= max num of generations
    3) cycle through each individual in the population
        3.A) perform mutation
        3.B) perform recombination ("crossover" in GA lingo)
        3.C) perform selection
    4) if stopping criterion has been met:
            exit and return best individual
        else:
            iter = iter + 1
            go back to step #3
```

![image](https://user-images.githubusercontent.com/43421608/220276093-8ac625c4-9d00-4df6-8177-2e6431a240c9.png)



[^1]:  https://en.wikipedia.org/wiki/Differential_evolution

# Project Description

## Use Genetic Algorithm to determine the optimum weight of stocks or asset classes in a given investment portfolio

<img src="https://www.pico.net/assets/kb/27-what-is-a-genetic-algorithm/genetic-algorithm-process-cycle.png">
<br>Figure - The evolutionary cycle of a typical evolutionary algorithm. Each block represents an operation on a population of candidate solutions.<br><br>

The purpose of this project was to determine optimum weights of assets in a given investment portfolio using *Genetic Algorithm*. In this case, *Sharpe ratio* was used as a **fitness function** with an aim to maximize the returns while minimizing the risk at the same time. **Heuristic Crossover and Arithmetic Crossover** techniques were employed for comparison along with a varying probability of **Mutation** for every new generation during each iteration. Finally, the set of asset weights which resulted in maximum expected portfolio return and minimum expected portfolio risk (standard deviation) was selected by optimizing the fitness function.
<br><br>This repository holds the data and jupyter notebook for the project.
The jupyter notebook contains steps and comments providing the complete details on approach and outcome acheived in this project.

### Acknowlegdement

Many snippets of the code used may have been taken from other open GitHub repositories to pace up the learning process. It is acknowledged here that data has been gathered from multiple sources. I am thankful to all of them for their mentorship and help.
Additional sources:

1. Monthly stock price data - Yahoo finance
2. Evolutionary Generational Cycle flow chart - pico.net/kb/what-is-a-genetic-algorithm/

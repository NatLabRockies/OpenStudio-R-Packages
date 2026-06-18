# OpenStudio R Packages

This code is designed to work with the [OpenStudio Server](https://github.com/NREL/OpenStudio-server) and may not be appropriate for solo use!
It contains modified versions of existing R packages to fit the parallelization needs of the OS-Server.
In most cases, the existing parallelization is replaced with one that takes an externally defined cluster object and then uses the `clusterApplyLB` or `parApplyLB` method in R::Parallel.

# Available Algorithms

These modified algorithms are available from the following R packages:

## [nsga2R](https://cran.r-project.org/web/packages/nsga2R/index.html)
* NSGA2 (Nondominated Sorting Genetic Algorithm 2) multi-objective optimization
* SPEA2 (Strength Pareto Evolutionary Algorithm 2) multi-objective optimization

## [GA](https://cran.r-project.org/package=GA)
* GA (optimization using genetic algorithms - single-objective optimization)
* GAIslands (optimization using Islanding genetic algorithms - single-objective optimization)

## [hydroPSO](http://www.rforge.net/hydroPSO/)
* PSO (Particle Swarm Optimization) single-objective optimization

## Questions?

Please contact @bball or @nllong with any question regarding this project. Thanks for you interest!


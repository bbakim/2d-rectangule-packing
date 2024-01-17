# 2d-rectangule-packing
Packing the given rectangles to the given area

For this problem, genetic algorithm is used to find better efficiency level in every iteration and bottom left algorithm to place rectangules.

The Bottom-Left algorithm is a method used to efficiently pack rectangular items into a rectangular container. It works by sorting the items in decreasing order of their heights (or widths, depending on the orientation of packing), and then placing each item in the bottom-left position where it fits, starting from the largest item. When placing an item, the algorithm tries to place it as far to the bottom and left as possible while still fitting within the container and without overlapping other items. This algorithm often results in a compact packing arrangement, especially when the items have varying dimensions.

The genetic algorithm is a type of optimization algorithm inspired by the process of natural selection and genetic evolution. It is commonly used to solve problems that involve finding the best solution from a large search space, where traditional methods might be impractical. In a genetic algorithm, a population of potential solutions (represented as individuals or chromosomes) evolves over generations through processes such as selection, crossover (recombination), and mutation. During each generation, individuals are selected based on their fitness (how well they solve the problem), and they produce offspring through crossover and mutation. Over time, the population tends to evolve towards better solutions, driven by the principles of natural selection, until a satisfactory solution is found or a termination criterion is met. Genetic algorithms are particularly useful for complex optimization problems where the search space is large or not well-defined.

Go to the folder where app.py is located.
Run this command: "python genetic-bla.py"
Enter file name which is located in the same folder with python file.
Enter efficiency rate to be achieved.
Output will be a png and gcode file.

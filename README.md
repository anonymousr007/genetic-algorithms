# Genetic Algorithms

![Genetic Algorithms](https://github.com/anonymousr007/genetic-algorithms/blob/main/Images/1_k3BNXRCK5RkHV91rQK06jw.jpeg)

> Genetic Algorithms are a family of search algorithms inspired by the principles of evolution in nature. By imitating the process of natural selection and reproduction, genetic algorithms can produce high-quality solutions for various problems involving search, optimization, and learning. At the same time, their analogy to natural evolution allows genetic algorithms to overcome some of the hurdles that are encountered by traditional search and optimization algorithms, especially for problems with a large number of parameters and complex mathematical representations.

## Table of Contents 

### Section 1: The Basics of Genetic Algorithms

- [1. An Introduction to Genetic Algorithms]()
  - [1.1 What are genetic algorithms?]()
    - [1.1.1 Darwinian evolution]()
    - [1.1.2 The genetic algorithms analogy]()
      - [1.1.2.1 Genotype]()
      - [1.1.2.2 Population]()
      - [1.1.2.3 Fitness function]()
      - [1.1.2.4 Selection]()
      - [1.1.2.5 Crossover]()
      - [1.1.2.6 Mutation]()
  - [1.2 The theory behind genetic algorithms]()
    - [1.2.1 The schema theorem]()
  - [1.3 Differences from traditional algorithms]()
    - [1.3.1 Population based]()
    - [1.3.2 Genetic representation]()
    - [1.3.3 Fitness function]()
    - [1.3.4 Probabilistic behavior]()
  - [1.4 Advantages of genetic algorithms]()
    - [1.4.1 Global optimization]()
    - [1.4.2 Handling complex problems]()
    - [1.4.3 Handling a lack of mathematical representation]()
    - [1.4.4 Resilience to noise]()
    - [1.4.5 Parallelism]()
    - [1.4.6 Continuous learning]()
  - [1.5 Limitations of genetic algorithms]()
    - [1.5.1 Special definitions]()
    - [1.5.2 Hyperparameter tuning]()
    - [1.5.3 Computationally intesive]()
    - [1.5.4 Premature convergence]()
    - [1.5.5 No guaranteed solution]() 
  - [1.6 Use cases of genetic algorithms]()
- [2. Understanding the Key Components of Genetic Algorithms]()
  - [2.1 Basic flow of a genetic algorithm]()
    - [2.1.1 Creating the initial population]()
    - [2.1.2 Calculate the fitness]()
    - [2.1.3 Applying selection, crossover, and mutation]()
    - [2.1.4 Checking the stopping conditions]()
  - [2.2 Selection methods]()
    - [2.2.1 Roulette wheel selection]()
    - [2.2.2 Stochastic universal sampling]()
    - [2.2.3 Rank-based selection]()
    - [2.2.4 Fitness scaling]()
    - [2.2.5 Tournament selection]()
  - [2.3 Crossover methods]()
    - [2.3.1 Single-point crossover]()
    - [2.3.2 Two-point and k-point crossover]()
    - [2.3.3 Uniform crossover]()
    - [2.3.4 Crossover for ordered lists]()
      - [2.3.4.1 Ordered crossover]()
  - [2.4 Mutation methods]()
    - [2.4.1 Flip bit mutation]()
    - [2.4.2 Swap mutation]()
    - [2.4.3 Inversion mutation]()
    - [2.4.4 Scramble mutation]()
  - [2.5 Real-coded genetic algorithms]()
    - [2.5.1 Blend crossover]()
    - [2.5.2 Simulated binary crossover]()
    - [2.5.3 Real mutation]()
  - [2.6 Understanding elitism]()
  - [2.7 Niching and sharing]()
    - [2.7.1 Serial niching versus parallel niching]()
  - [2.8 The art of solving problems using genetic algorithms]()

### Section 2: Solving Problems using Genetic Algorithms

- [3. Using the DEAP Framework]()
  - [3.1 Technical requirements]()
  - [3.2 Introduction to DEAP]()
  - [3.3 Using the creator module]()
    - [3.3.1 Creating the Fitness class]()
        - [3.3.1.1 Defining the fitness strategy]()
        - [3.3.1.2 Storing the fitness values]()
    - [3.3.2 Creating the Individual class]()
  - [3.4 Using the Toolbox class]()
    - [3.4.1 Creating genetic operators]()
    - [3.4.2 Creating the population]()
    - [3.4.3 Calculating the fitness]()
  - [3.5 The OneMax problem]()
  - [3.6 Solving the OneMax problem with DEAP]()
    - [3.6.1 Choosing the chromosome]()
    - [3.6.2 Calculating the fitness]()
    - [3.6.3 Choosing the genetic operators]()
    - [3.6.4 Setting the stopping condition]()
    - [3.6.5 Implementing with DEAP]()
      - [3.6.5.1 Setting up]()
      - [3.6.5.2 Evolving the solution]()
      - [3.6.5.3 Running the program]()
  - [3.7 Using built-in algorithms]()
    - [3.7.1 The Statistics object]()
    - [3.7.2 The algorithm]()
    - [3.7.3 The logbook]()
    - [3.7.4 Running the program]()
    - [3.7.5 Adding the hall of fame]()
  - [3.8 Experimenting with the algorithm's settings]()
    - [3.8.1 Population size and number of generations]()
    - [3.8.2 Crossover operator]()
    - [3.8.3 Mutation operator]()
    - [3.8.4 Selection operator]()
      - [3.8.4.1 Tournament size and relation to mutation probability]()
      - [3.8.4.2 Roulette wheel selection]()
- [4. Combinational Optimization]()
  - [4.1 Technical requirements]()
  - [4.2 Search problems and combinational optimization]()
  - [4.3 Solving the knapsack problem]()
    - [4.3.1 The Rosetta Code knapsack 0-1 problem]()
    - [4.3.2 Solution representation]()
    - [4.3.3 Python problem representation]()
    - [4.3.4 Genetic algorithms solution]()
  - [4.3 Solving the Traveling Salesman Problem [TSP]]()
    - [4.3.1 TSPLIB benchmark files]()
    - [4.3.2 Solution representation]()
    - [4.3.3 Python problem representation]()
    - [4.3.4 Genetic algorithms solution]()
    - [4.3.5 Improving the results with enhanced exploration and elitism]()
  - [4.4 Solving the Vehicle Routing Problem [VRP]]()
    - [4.4.1 Solution representation]()
    - [4.4.2 Python problem representation]()
    - [4.4.3 Genetic algorithms solution]()
- [5. Constraint Satisfaction]()
  - [5.1 Technical requirements]()
  - [5.2 Constraint satisfaction in search problems]()
  - [5.3 Solving the N-Queens problem]()
    - [5.3.1 Solution representation]()
    - [5.3.2 Python problem representation]()
    - [5.3.3 Genetic algorithms solution]()
  - [5.4 Solving the Nurse scheduling problem]()
    - [5.4.1 Solution representation]()
    - [5.4.2 Hard constraints versus soft constraints]()
    - [5.4.3 Python problem representation]()
    - [5.4.4 Genetic algorithms solution]()
  - [5.5 Solving the graph coloring problem]()
    - [5.5.1 Solution representation]()
    - [5.5.2 Using hard and soft constraints for the graph coloring problem]()
    - [5.5.3 Python problem representation]()
    - [5.5.4 Genetic algorithms solution]()
- [6. Optimizing Continuous Functions]()
  - [6.1 Technical requirements]()
  - [6.2 Chromosomes and genetic operators for real numbers]()
  - [6.3 Using DEAP with continuous functions]()
  - [6.4 Optimizing the Eggholder function]()
    - [6.4.1 Optimizing the Eggholder function with genetic algorithms]()
    - [6.4.2 Improving the speed with an increased mutation rate]()
  - [6.5 Optimizing Himmelblau's function]()
    - [6.5.1 Optimizing Himmelblau's function with genetic algorithms]()
    - [6.5.2 Using niching and sharing to find multiple solutions]()
  - [6.6 Simionescu's function and constrained optimization]()
    - [6.6.1 Constrained optimization with genetic algorithms]()
    - [6.6.2 Optimizing Simionescu's function using genetic algorithms]()
    - [6.6.3 Using constraints to find multiple solutions]()

### Section 3: Artificial Intelligence Applications of Genetic Algorithms

- [7. Enhancing Machine Learning Models Using Feature Selection]()
  - [7.1 Technical requirements]()
  - [7.2 Supervised machine learning]()
    - [7.2.1 Classification]()
    - [7.2.2 Regression]()
    - [7.2.3 Supervised learning algorithms]()
  - [7.3 Feature selection in supervised learning]()
  - [7.4 Selecting the features for the Friedman-1 regression problem]()
    - [7.4.1 Solution representation]()
    - [7.4.2 Python problem representation]()
    - [7.4.3 Genetic algorithms solution]()
  - [7.5 Selecting the features for the classification Zoo dataset]()
    - [7.5.1 Python problem representation]()
    - [7.5.2 Genetic algorithms solution]()
- [8. Hyperparameter Tuning of Machine Learning Models]()
  - [8.1 Technical requirements]()
  - [8.2 Hyperparameters in machine learning]()
    - [8.2.1 Hyperparameter tuning]()
    - [8.2.2 The Wine dataset]()
    - [8.2.3 The adaptive boosting classifier]()
  - [8.3 Tuning the hyperparameters using a genetic grid search]()
    - [8.3.1 Testing the classifier's default performance]()
    - [8.3.2 Running the conventional grid search]()
    - [8.3.3 Running the genetic algorithm-driven grid search]()
  - [8.4 Tuning the hyperparameters using a direct genetic approach]()
    - [8.4.1 Hyperparameter representation]()
    - [8.4.2 Evaluating the classifier accuracy]()
    - [8.4.3 Tuning the hyperparameters using genetic algorithms]()
- [9. Architecture Optimization of Deep Learning Networks]()
  - [9.1 Technical requirements]()
  - [9.2 Artificial neural networks and deep learning]()
    - [9.2.1 Multilayer Perceptron]()
    - [9.2.2 Deep learning and convolutional neural networks]()
  - [9.3 Optimizing the architecture of a deep learning classifier]()
    - [9.3.1 The Iris flower dataset]()
    - [9.3.2 Representing the hidden layer configuration]()
    - [9.3.3 Evaluating the classifier's accuracy]()
    - [9.3.4 Optimizing the MLP architecture using genetic algorithms]()
  - [9.4 Combining architecture optimization with hyperparameter tuning]()
    - [9.4.1 Solution representation]()
    - [9.4.2 Evaluating the classifier's accuracy]()
    - [9.4.3 Optimizing the MLP's combined configuration using genetic algorithms]()
- [10. Reinforcement Learning with Genetic Algorithms]()
  - [10.1 Technical requirements]()
  - [10.2 Reinforcement learning]()
    - [10.2.1 Genetic algorithms and reinforcement learning]()
  - [10.3 OpenAI Gym]()
    - [10.3.1 The env interface]()
  - [10.4 Solving the MountainCar environment]()
    - [10.4.1 Solution representation]()
    - [10.4.2 Evaluating the solution]()
    - [10.4.3 Python problem representation]()
    - [10.4.4 Genetic algorithms solution]()
  - [10.5 Solving the CartPole environment]()
    - [10.5.1 Controlling the CartPole with a neural network]()
    - [10.5.2 Solution representation and evaluation]()
    - [10.5.3 Python problem representation]()
    - [10.5.4 Genetic algorithms solution]()

### Section 4: Related Technologies

- [11. Genetic Image Reconstruction]()
  - [11.1 Technical requirements]()
  - [11.2 Reconstruction images with polygons]()
  - [11.3 Image processing in Python]()
    - [11.3.1 Python image processing libraries]()
      - [11.3.1.1 The Pillow library]()
      - [11.3.1.2 The scikit-image library]()
      - [11.3.1.3 The opencv-python library]()
    - [11.3.2 Drawing images with polygons]()
    - [11.3.3 Measuring the difference between images]()
      - [11.3.3.1 Pixel-based Mean Squared Error]()
      - [11.3.3.2 Structural Similarity (SSIM)]()
  - [11.4 Using genetic algorithms to reconstruct images]()
    - [11.4.1 Solution representation and evaluation]()
    - [11.4.2 Python problem representation]()
    - [11.4.3 Genetic algorithm implementation]()
      - [11.4.3.1 Adding a callback to the genetic run]()
    - [11.4.4 Image reconstruction results]()
      - [11.4.4.1 Using pixel-based Mean Squared Error]()
      - [11.4.4.2 Using the SSIM index]()
      - [11.4.4.3 Other experiments]()
- [12. Other Evolutionary and Bio-Inspired Computation Techniques]()
  - [12.1 Technical requirements]()
  - [12.2 Evolutionary computation and bio-inspired computing]()
  - [12.3 Genetic programming]()
    - [12.3.1 Genetic programming example – even parity check]()
    - [12.3.2 Genetic programming implementation]()
      - [12.3.2.1 Simplifying the solution]()
  - [12.4 Particle swarm optimization]()
    - [12.4.1 PSO example – function optimization]()
    - [12.4.2 Particle swarm optimization implementation]()
  - [12.5 Other related techniques]()
    - [12.5.1 Evolution strategies]()
    - [12.5.2 Differential evolution]()
    - [12.5.3 Ant colony optimization]()
    - [12.5.4 Artificial immune systems]()
    - [12.5.5 Artificial life]()

## References

- 𝐑𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲 𝐨𝐧 𝐆𝐞𝐧𝐞𝐭𝐢𝐜 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦𝐬: https://github.com/anonymousr007/genetic-algorithms
- 𝐃𝐄𝐀𝐏 𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤: https://github.com/DEAP/deap
- 𝐃𝐨𝐜𝐬 𝐨𝐟 𝐃𝐄𝐀𝐏 𝐅𝐫𝐚𝐦𝐞𝐰𝐨𝐫𝐤: https://deap.readthedocs.io/en/master
- 𝐖𝐢𝐤𝐢𝐩𝐞𝐝𝐢𝐚 𝐨𝐟 𝐆𝐞𝐧𝐞𝐭𝐢𝐜 𝐀𝐥𝐠𝐨𝐫𝐢𝐭𝐡𝐦𝐬: https://en.wikipedia.org/wiki/Genetic_algorithm
- 𝐋𝐢𝐧𝐤𝐞𝐝𝐢𝐧 𝐏𝐨𝐬𝐭 𝐏𝐚𝐫𝐭-1: https://www.linkedin.com/posts/anonymousr007_computing-algorithms-startup-activity-6891668751045980160-4UTx
- 𝐋𝐢𝐧𝐤𝐞𝐝𝐢𝐧 𝐏𝐨𝐬𝐭 𝐏𝐚𝐫𝐭-2: https://www.linkedin.com/posts/anonymousr007_computing-deeplearning-algorithms-activity-6892040549533040640-CUeW

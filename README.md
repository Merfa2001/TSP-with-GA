# TSP-with-GA
 Solving the TSP problem with genetic algorithm
#### Introduction
This repository contains a Python implementation of a Genetic Algorithm (GA) designed to find an approximate solution to the Travelling Salesman Problem (TSP). The TSP is a well-known NP-hard problem in combinatorial optimization. The goal is to find the shortest possible route that visits each city once and returns to the origin city.

#### Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.x
- Matplotlib (for plotting the results)

#### Installation
1. Clone this repository to your local machine.
   ```bash
   git clone https:[//github.com/your-username/your-repository.git](https://github.com/Merfa2001/TSP-with-GA.git)
   ```
2. Install the required packages.
   ```bash
   pip install matplotlib
   ```

#### Usage
Run the script from the command line:
```bash
python tsp_ga.py
```

This will execute the genetic algorithm and output the best route found along with a plot of the cost function showing improvements over generations.

#### Output
The program outputs:
- **Final Best Tour Plot**: A graphical representation of the best route found by the genetic algorithm.
  
![download](https://github.com/Merfa2001/TSP-with-GA/assets/146805956/9ffde772-9911-4150-a073-cc482fb89e8a)

- **Cost Function Improvement Plot**: A plot showing the decrease in total travel distance (cost) over generations, which demonstrates the efficiency of the genetic algorithm in optimizing the route.
  
  ![download (1)](https://github.com/Merfa2001/TSP-with-GA/assets/146805956/f5c3a6f8-d34e-40b6-b5fe-7a721863ebd2)


#### Results
After running the genetic algorithm with the given parameters (e.g., 50 cities, 100 generations), you will see:
- The final best route that the algorithm computed.
- A decreasing trend in the plot as the GA evolves, indicating improvement in finding shorter routes.

The actual output will vary depending on the specific random initialization and GA parameters such as population size, mutation rate, and number of generations.

#### Contributing
Feel free to fork this repository and submit pull requests. You can also open an issue if you find any bugs or have suggestions for additional features.

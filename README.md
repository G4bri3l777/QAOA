# Quantum Approximate Optimization Algorithm (QAOA) for Graph 3-Coloring Problem

## Overview

This project implements the Quantum Approximate Optimization Algorithm (QAOA) to address the Graph 3-Coloring Problem. The solution leverages quantum computing techniques to provide an efficient approach to this combinatorial problem.

## Libraries Used

This project utilizes the following Python libraries:

- `numpy`: Provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
- `networkx`: A library used for the creation, manipulation, and study of complex networks of nodes and edges.
- `qiskit` (version 1.1): An open-source quantum computing framework for working with quantum circuits and algorithms.
- `qiskit_ibm_runtime`: Provides tools for interfacing with IBM Quantum's cloud-based quantum computing services.
- `scipy.optimize`: A module from SciPy used for optimization tasks, including the `minimize` function used in this project.
- `matplotlib`: A plotting library for creating static, animated, and interactive visualizations in Python.
- `itertools`: A library providing functions to work with iterators, used here for generating combinations.

## Setup

To get started with this project, you need to have the following Python libraries installed. You can install them using `pip`:

```bash
pip install numpy networkx qiskit==1.1 qiskit_ibm_runtime scipy matplotlib
```

## Usage

To use this project, follow these steps:

1. **Initialize Quantum Circuit:**
   Create and configure the quantum circuit for the QAOA algorithm.

2. **Define Graph:**
   Utilize NetworkX to create and manipulate the graph for the 3-coloring problem.

3. **Run QAOA:**
   Apply the QAOA algorithm to solve the 3-coloring problem.

4. **Visualize Results:**
   Use Matplotlib to visualize the results and performance of the QAOA algorithm.

## Contributing

We welcome contributions to this project. If you would like to contribute, please follow these guidelines:

1. **Fork the Repository:** Create a personal copy of the repository by forking it on GitHub.

2. **Create a Branch:** Make a new branch for your changes. Use a descriptive name for the branch that reflects the changes you are making.

3. **Make Changes:** Implement your changes or additions.

4. **Write Tests:** If applicable, write tests for your changes.

5. **Submit a Pull Request:** Push your changes to your forked repository and submit a pull request to the main repository. Describe your changes and reference any related issues.

6. **Review:** The pull request will be reviewed, and feedback may be provided. You may need to make additional changes based on the review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **IBM Quantum:** For the Qiskit Runtime Service and SamplerV2.
- ** Dr. Ilya Safro for his guidance, discussion and mentoring.



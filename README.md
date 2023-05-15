# Network Algorithms Library

The Network Algorithms Library is a Python library that provides a collection of algorithms and models for network optimization problems. It offers implementations of various linear programming models and algorithms, as well as utilities for demonstration and third-party visualization.

## Features

- Implementation of linear programming algorithms such as <u>simplex, interior point, dual simplex, cutting plane, branch and bound, column generation, Dantzig-Wolfe decomposition, and benders' decomposition</u>.
- Models for network optimization problems including <u>transportation problem, mixed integer linear programming (MILP), binary linear programming, stochastic linear programming, multiple objective linear programming (MOLP)</u>, and more.
- Utilities for demonstration, test examples, and third-party visualization integration.

## Installation

### Prerequisites

- Python (version X.X.X)
- Git

### Clone the Repository

```bash
git clone https://github.com/your-username/network-algorithms.git
cd network-algorithms
```

### Install Dependencies

```shell
pip install -r requirements.txt
```

To install the packages inside the Network Algorithms Library:

```shell
pip install -e .
```

### Running Tests

```shell
python -m unittest discover tests
```

### Directory Structure

The directory structure of the Network Algorithms Library is organized as follows:

- `algorithms/`: Contains algorithm implementations.
- `models/`: Includes models for network optimization problems.
- `data/`: Stores example data and test cases.
- `third_party/`: Houses third-party packages and dependencies.
- `tests/`: Contains test files for unit testing.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: Provides an overview of the library (this file).
- `LICENSE`: Contains the license information.
- `setup.py`: Defines the package setup and distribution.
- `requirements.txt`: Lists the library's dependencies.

## Example Usage

Here's a simple example that demonstrates how to use the library to solve a transportation problem:

```python
from network_algorithms.models import transportation
from network_algorithms.algorithms import simplex

# Define the transportation problem
# ...

# Solve the problem using the simplex algorithm
solution = simplex.solve(transportation_problem)

# Print the optimal solution
print(solution)
```

For detailed usage instructions and examples, please refer to the [documentation]().

## Documentation

The complete documentation of the Network Algorithms Library can be found [here]().

## Development

If you wish to contribute or make modifications to the Network Algorithms Library, please read the following contents.

### Roadmap

We have an exciting roadmap ahead for the Network Algorithms Library, with the following planned enhancements:

- Addition of non-linear programming models and algorithms.
- Support for additional programming languages like C++ and Julia (maybe Rust in the future).
- Enhanced visualization capabilities and integration with popular graph visualization libraries.

### Contributing

Contributions are welcome! If you want to contribute to the Network Algorithms Library, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

### Contact

If you have any questions, suggestions, or feedback, feel free to reach out to us at [2568682045@qq.com].

## Acknowledgements

## License

The Network Algorithms Library is licensed under the [MIT License](LICENSE).

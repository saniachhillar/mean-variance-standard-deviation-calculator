# Mean-Variance-Standard-Deviation Calculator

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A Python project that calculates descriptive statistics for a 3×3 matrix using NumPy. Developed as part of the **FreeCodeCamp Data Analysis with Python Certification** to demonstrate proficiency in numerical computing, matrix operations, and statistical analysis.

---

## Overview

The program accepts a list of **nine numerical values**, converts it into a **3×3 NumPy array**, and computes descriptive statistics across **rows**, **columns**, and the **entire matrix**.

## Features

- Calculate mean
- Calculate variance
- Calculate standard deviation
- Find maximum values
- Find minimum values
- Calculate sums
- Validate input (raises a `ValueError` if fewer than nine values are provided)

## Technologies Used

- Python 3
- NumPy
- Git
- GitHub

## Project Structure

```text
.
├── mean_var_std.py
├── main.py
├── test_module.py
├── requirements.txt
└── README.md
```

## Example

### Input

```python
calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
```

### Output

```python
{
    'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
    'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
    'standard deviation': [[2.449489742783178, 2.449489742783178, 2.449489742783178],
                           [0.816496580927726, 0.816496580927726, 0.816496580927726],
                           2.581988897471611],
    'max': [[6, 7, 8], [2, 5, 8], 8],
    'min': [[0, 1, 2], [0, 3, 6], 0],
    'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```

## Installation

Clone the repository:

```bash
git clone https://github.com/saniachhillar/mean-variance-standard-deviation-calculator.git
```

Navigate to the project directory:

```bash
cd mean-variance-standard-deviation-calculator
```

Install the required dependency:

```bash
pip install numpy
```

## Usage

Run the project:

```bash
python main.py
```

Run the unit tests:

```bash
python test_module.py
```

## Skills Demonstrated

- Python programming
- NumPy array manipulation
- Matrix reshaping
- Descriptive statistics
- Axis-based computations
- Input validation
- Unit testing
- Git & GitHub workflow

## Project Status

✅ Completed

All unit tests pass successfully.

## Certification

This project was completed as part of the FreeCodeCamp Data Analysis with Python Certification.

## License

This project is licensed under the MIT License.

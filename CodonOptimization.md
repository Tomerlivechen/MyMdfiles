# Codon Optimization Program

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Optimization Options](#optimization-options)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

This Python program is designed for codon optimization, which involves converting a protein sequence into its corresponding DNA sequence with optimized codons. Codon optimization can be useful for improving protein expression in various biological applications. The program provides options for different optimization strategies and removes unwanted cut sites, such as restriction enzyme recognition sites and miRNA binding domains.

## Features

- Codon optimization based on different strategies.
- Removal of unwanted cut sites.
- Efficient conversion of protein sequence to optimized DNA sequence.
- Ability to customize optimization parameters.

## Getting Started

### Prerequisites

- Python 3.x
- tkinter library (usually included with Python)

### Installation

1. Clone or download this repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Install the required libraries if not already installed:

   ```bash
   pip install tkinter
   ```

## Usage

1. Run the program by executing the `codon_optimization.py` script.
2. The program will open a graphical user interface (GUI) for input and options.

## Optimization Options

The program offers several optimization options:

- Optimization for muscle expression.
- Optimization for high GC content.
- Optimization for muscle expression and low uridine content.
- Optimization based on a specific optimization algorithm (JHU).

You can select your preferred optimization type from the provided options.

## Output

The program will generate an optimized DNA sequence based on the input protein sequence and chosen optimization strategy. It will also remove unwanted cut sites and miRNA binding domains to ensure the sequence complies with your specifications.

The optimized DNA sequence will be saved to a text file with the name you provide in the GUI.

## Contributing

Contributions are welcome. If you have suggestions or encounter issues, please open a GitHub issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

[Dr. Tomer Chen](https://github.com/Tomerlivechen)

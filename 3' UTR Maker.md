# Mouse 3' UTR Maker

## Description
The "3' UTR Maker" is a Python-based graphical user interface (GUI) application designed to help users generate 3' untranslated region (UTR) sequences for mouse miRNA. This tool allows for the creation of custom 3' UTR sequences by selecting miRNAs, adjusting UTR length, and specifying the number of miRNA copies. The generated UTR sequence avoids bad miRNA sequences and customizes based on user input.

## Features
- **miRNA Selection**: Choose from a list of miRNAs to include in the UTR.
- **Adjustable UTR Length**: Input the desired length for the generated UTR sequence.
- **Number of miRNA Copies**: Specify how many copies of each miRNA should be included in the sequence.
- **Bad miRNA Sequence Detection**: The program checks the generated UTR sequence for bad miRNA sequences and replaces them.
- **Output Display**: The generated UTR sequence is shown in the output field and can be customized further.

## Components
- **Graphical User Interface (GUI)**: Built with Tkinter for a user-friendly interface.
- **MiRNA Data**: Predefined miRNA names, sequences, and loci information.
- **Sequence Generation**: The tool constructs the UTR sequence by placing selected miRNAs at appropriate locations, with checks for undesirable sequences.
- **Sequence Validation**: Verifies and replaces bad miRNA sequences in the generated UTR.

## User Information
- **User Role**: The application is intended for users in the field of molecular biology who are interested in creating custom 3' UTR sequences for research purposes.
- **Features Available to Users**:
  - **MiRNA Selection**: Users can select miRNAs from a predefined list.
  - **UTR Length**: Users can input the desired length of the UTR.
  - **MiRNA Copies**: Users can specify how many times each miRNA should appear in the UTR.
  - **Sequence Generation**: The application generates and validates the UTR sequence.

## Requirements
- **Python**: Version 3.x or higher is required.
- **Libraries**:
  - Tkinter (for the GUI)
  - NumPy (for handling certain array operations)
  - Random (for sequence generation)
  - Math (for randomization and calculations)

## Installation
1. Ensure Python 3.x is installed on your system.
2. Clone the repository to your local machine.
3. Install necessary dependencies (`Tkinter`, `NumPy`).
4. Run the Python script to launch the GUI application.

## Licensing
This program is private, and the code is not intended for public distribution.

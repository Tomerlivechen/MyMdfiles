# Reverse Complement RNA Program

This program provides a graphical user interface (GUI) for analyzing DNA sequences. It calculates the reverse, complement, reverse complement, RNA conversion, and reverse complement RNA of a given DNA sequence.

## Features

1. **Reverse**: Outputs the reverse of the entered DNA sequence.
2. **Complement**: Calculates the complement of the DNA sequence.
3. **Reverse Complement**: Computes the reverse complement of the DNA sequence.
4. **RNA**: Converts the DNA sequence into RNA by replacing all thymine (`T`) nucleotides with uracil (`U`).
5. **Reverse Complement RNA**: Computes the reverse complement and converts it to RNA.

## User Interface

### Widgets:
- **Input Sequence**: Text box for the user to input the DNA sequence.
- **Reverse**: Displays the reverse of the input DNA sequence.
- **Complement**: Displays the complement of the DNA sequence.
- **Reverse Complement**: Displays the reverse complement of the DNA sequence.
- **RNA**: Displays the RNA conversion of the DNA sequence.
- **Reverse Complement RNA**: Displays the RNA conversion of the reverse complement.
- **Run Button**: Executes the calculations based on the entered sequence.

### Layout:
The GUI is organized with labeled sections for each feature, providing results in distinct text boxes next to their respective labels.

## How to Use

1. Run the program.
2. Enter a valid DNA sequence into the `Insert sequence` text box.
3. Click the **Run** button.
4. View the calculated results in the corresponding text boxes:
   - **Reverse**: Reverse sequence.
   - **Complement**: Complement sequence.
   - **Reverse Complement**: Reverse complement sequence.
   - **RNA**: RNA equivalent of the sequence.
   - **Reverse Complement RNA**: RNA equivalent of the reverse complement.

## Requirements
- Python 3.x
- Libraries:
  - `random`
  - `math`
  - `tkinter`
  - `numpy`
  - `warnings`

## Example

### Input:
```
ATGCGTAC
```

### Output:
- **Reverse**: CATGCGTA
- **Complement**: TACGCATG
- **Reverse Complement**: CATGCGTA
- **RNA**: AUGCGUAC
- **Reverse Complement RNA**: CAUGCGUA

## Notes
- Ensure the input sequence is valid DNA (composed of A, T, C, G only).
- The program replaces `T` with `U` for RNA conversions.




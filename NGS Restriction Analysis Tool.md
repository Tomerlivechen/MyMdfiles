
# NGS Restriction Analysis Tool

## Description

This Python-based tool provides a graphical user interface (GUI) for performing NGS restriction analysis. It processes sequence data files and classifies sequences into "cut" and "uncut" categories based on predefined patterns. The tool uses the BioPython library for sequence alignment and analysis and can handle custom sequence patterns for more flexible analysis.

## Features

- **GUI for easy interaction**: Built using `tkinter` for seamless user experience.
- **Customizable sequence analysis**: Supports multiple types of sequence analysis (e.g., "22-24", "64-66", or custom).
- **Automatic classification**: Sequences are automatically classified as "cut" or "uncut" based on pairwise alignment.
- **Result Export**: The results (cut/uncut sequence counts) are exported to a text file.

## Requirements

- **Python 3.x** or later
- **BioPython**: For sequence alignment and biological sequence handling
- **tkinter**: For the GUI (usually comes pre-installed with Python)
- **Additional libraries**:
    - `os`
    - `csv`

You can install BioPython using pip:
```bash
pip install biopython
```

## Usage

1. **Launch the GUI**:
   - Run the script: `python NGS_Restriction_Analysis.py`
   
2. **Input Folder and Export File**:
   - Enter the path to the folder containing CSV files with sequence data.
   - Enter a name for the output file where the results will be saved.
   
3. **Sequence Input**:
   - Define the validation, full, and cut sequences for both forward and reverse strands.
   
4. **Select Analysis Type**:
   - Choose between predefined sequence types or input custom sequences for analysis.

5. **Run Analysis**:
   - Click the "Run Analysis" button to start processing the sequences. The results will be written to the specified export file.

## File Format for Input Sequences

The input sequence files should be in CSV format with each sequence on a new line. The sequences will be analyzed according to the selected parameters.

Example of sequence format:
```csv
ACTCGGGAAATTACA
taatggaggagagactcgggaaATTACAGGCTCTGCAAAGTTCTTTGAAAGAGCAACAAAATGGCTTCAACTATCTGAGTGACACTGTGAAGGAGATGGCCAAGAAAGCACCTTCAGAAATATGCCAGAAATATCTGTCAGAATTTGAAGAGATTGAGGGGCACTGGAAGAAACTTTCCTCCCAGTTGGTGGAAAGCTGCCAAAAGCTAGAAGAACATATGAATAAACTTCGAAAATTTCAGAATCACAT
```

## Example Output

The output will show the count of uncut and cut sequences, saved in a `.txt` file:
```
Uncut sequences: 150
Cut sequences: 50
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

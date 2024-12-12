# Graph Maker Tool

## Project Overview
The Graph Maker Tool is a user-friendly graphical user interface (GUI) designed to create customized graphs from Excel data. It supports multiple plot types such as bar plots, box plots, strip plots, and p-value tables, allowing researchers and analysts to visualize their data effectively.

## Features
- **Data Import**: Load data from an Excel file with ease.
- **Flexible Plot Types**: Create Bar plots, Box plots, Strip plots, and export p-value tables.
- **Statistical Analysis**: Generate Tukey-Kramer p-values for comparison.
- **Customizable Graphs**: Adjust graph size, axis labels, and font sizes for tailored output.
- **Export Options**: Save generated graphs as images and export p-value tables as CSV.
- **GUI Interface**: Built with Tkinter for a seamless user experience.

## Technologies Used
- **Python**: The main programming language.
- **Tkinter**: For building the graphical user interface.
- **Plotly**: For generating interactive and publication-ready plots.
- **Pandas and NumPy**: For data manipulation.
- **SciPy and Scikit-Posthocs**: For statistical computations.
- **OpenPyXL**: To handle Excel files.

## Requirements
- Python 3.x
- Required libraries: `pandas`, `numpy`, `scipy`, `plotly`, `openpyxl`, `requests`, `datetime`, `kaleido`, `scikit_posthocs`

## How to Use
1. **Input File Path**: Provide the path to your Excel file in the GUI.
2. **Specify Sheet Name**: Enter the sheet name containing the data.
3. **Configure Graph Options**:
   - Define x-axis and y-axis labels.
   - Choose the graph title.
   - Select graph size and font size.
4. **Export Folder**: Specify the folder where the output files will be saved.
5. **Select Plot Type**: Choose the desired plot type (Bar, Box, Strip, Pval) and click the respective button to generate the graph.
6. **Save Outputs**: Export graphs as images and p-value tables as CSV files.

## Code Structure
- **Data Handling**: Reads and validates Excel files, extracts data, and processes it for visualization.
- **Graph Generation**: Functions for creating various plot types using Plotly.
- **Statistical Analysis**: Tukey-Kramer posthoc tests for pairwise comparisons.
- **GUI Management**: Tkinter-based interface for user interaction.
- **Error Handling**: Ensures valid input and provides informative error messages.

## License
This project is licensed under the [MIT License](LICENSE).

---
For additional questions, contact [TomerLiveChenWork.com](mailto:TomerLiveChenWork.com).

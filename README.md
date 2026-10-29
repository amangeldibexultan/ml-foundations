# ML Foundations

My learning repository for Python and machine learning fundamentals,
with a long-term goal of becoming an AI/LLM engineer.

## Completed work

### Python Foundations
Notebook: [01_python_foundations.ipynb](01_python_foundations.ipynb)

Topics practiced:
- Functions, lists, and dictionaries
- Loops and list comprehensions
- Exception handling
- Standard library imports

Implemented exercises:
1. Word frequency counter
2. Filtering a list of dictionaries
3. Duplicate detection
4. Min-max normalization with input validation
5. Reproducible train/test splitting without scikit-learn

### NumPy Basics
Notebook: [02_numpy_basics.ipynb](02_numpy_basics.ipynb)

Practiced array operations, indexing, boolean filtering,
axis-based aggregations, broadcasting, reshaping, and copying.

Implemented column-wise min-max normalization with constant-column
handling and checked the result using np.allclose().

### pandas Basics
Notebook: [03_pandas_basics.ipynb](03_pandas_basics.ipynb)

Practiced column selection, filtering, sorting, grouping,
missing-value handling, duplicate removal, and CSV input/output.

Implemented and checked a reusable student data cleaning function.

### Data Visualization
Notebook: [04_data_visualization.ipynb](04_data_visualization.ipynb)

Created bar charts, annotated scatter plots, histograms,
and line plots using basketball practice data.
Compared two players and saved a chart as PNG.

## How to run

1. Download a notebook from this repository.
2. Open it in Google Colab or Jupyter Notebook.
3. Run all cells from top to bottom.

### Dependencies

- 01_python_foundations.ipynb: Python standard library only.
- 02_numpy_basics.ipynb: numpy.
- 03_pandas_basics.ipynb: pandas.
- 04_data_visualization.ipynb: pandas and matplotlib.

All required packages are preinstalled in Google Colab.

For local use, install the packages:
pip install numpy pandas matplotlib

CSV and PNG files are generated when the corresponding cells are run.

## Next steps
- First machine learning project

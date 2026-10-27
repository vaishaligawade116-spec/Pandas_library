# Pandas Library Practice

A beginner-friendly Jupyter Notebook covering the fundamentals of **Pandas**, a Python library used for data analysis, data cleaning, and data manipulation.

## Contents

The `pandas.ipynb` notebook includes examples and practice code for:

- **Setup and imports** — installing Pandas and importing `pandas` and `numpy`
- **Series and DataFrames** — creating one-dimensional Series and two-dimensional DataFrames from lists, dictionaries, and NumPy arrays
- **Attributes and inspection** — checking shape, columns, index, data types, size, values, and memory usage
- **Exploring data** — using `head()`, `tail()`, `info()`, and `describe()`
- **Selection and indexing** — selecting columns and rows, and working with `loc`, `iloc`, `at`, `iat`, and `set_index()`
- **Filtering and Boolean indexing** — selecting rows that match conditions
- **Adding, modifying, and dropping data** — updating columns and removing rows or columns
- **Handling missing data** — identifying and working with missing values
- **Sorting and ranking** — arranging data and assigning ranks
- **Aggregation and statistics** — calculating summary statistics
- **GroupBy operations** — grouping data and applying aggregate operations

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- Pandas
- NumPy

## Setup

Install the required libraries:

```bash
pip install pandas numpy jupyter
```

## Run the notebook

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `pandas.ipynb`.
5. Run the cells from top to bottom. If a cell depends on variables created earlier, run those earlier cells first.

## Import libraries

```python
import pandas as pd
import numpy as np
```

## Learning goals

After working through this notebook, you should be able to:

- Create and inspect Pandas Series and DataFrames.
- Select, index, and filter rows and columns.
- Add, update, and remove data.
- Identify and handle missing values.
- Sort data and calculate basic statistics.
- Group data and summarize results.

## Project structure

```text
.
├── pandas.ipynb
└── README.md
```

## Notes

This repository is for learning and practice. The notebook contains code examples and explanations; run the cells in order to follow the workflow and see the results.

## Author

Created as a Pandas learning and practice notebook.

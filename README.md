Read assessment.ipynb.

Solution in dash_app.py

Main optimization:

Data Loading

Initial Code (copy.py): Reads data using cudf.read_csv() from a single CSV file.

Final Optimization (dash_app.py): Reads data using dask_cudf.read_csv() from multiple CSV files using a wildcard pattern.

## Project Title: ETL Extract, Transform, and Load Lab

### 1. Project Overview

This project carries out Full and Incremental Extraction for an Indian Sweet Shop's dataset `mitai_sales_data`, applies useful transformations, and loads it into a structured format.

### 2. Contents

- `etl_extract.ipynb`: Jupyter Notebook that includes simulating synthetic data, Full and Incremental Extraction, transforming the full data and the incremental data.
- `etl_load.ipynb`: Jupyter Notebook where the transformed data is loaded into a structured destination.
- `last_extraction.txt`: Stores the latest extraction date and time.
- `mitai_sales_data.csv`: Simulated synthetic data.
- `initial_last_extraction_date.png`: Screenshot showing the *initial* last extraction date.
- `updated_last_extraction_date.pdg`: Screenshot showing the *updated* last extraction date.
- `transformed_full.csv`: Transformed *fully extracted* data.
- `transformed_incremental.csv`: Transformed *incrementally extracted* data.
- `loaded_data/`: Folder containing the outputs of the 'Loading' phase.

### 3. Description of what the notebook `etl_extract.ipynb` does:

1. Simulates synthetic mitai sales data for an Indian sweet shop for the months of November and December 2024.
2. Implements full extraction on the mitai sales data.
3. Implements incremental extraction since the last extraction date.
4. Updates `last_extraction.txt` to the most recent update time.
5. Transforms the fully extracted and incremetally extracted data by converting data types, handling missing values, removing duplicates, and categorizing the 'Amount'.

### 3. Description of what the notebook `etl_load.ipynb` does:

1. Loads both transformed files into Parquet (using pandas.to parquet())
2. Previews the stored results (using pd.read_paraquet() then .head())
3. Saves the outputs in the 'loaded_data/' folder.

### 4. Tools used:

Python, Pandas, Jupyter Notebook, PyArrow.

### 5. How to reproduce:

- Ensure you have the necessary libraries installed (`pip install pandas pyarrow jupyter`)
- Clone the repository
- Follow the notebooks in order (`etl_extract.ipynb` -> `etl_load.ipynb`)
- Verify the outputs by checking 'loaded_data/' folders.

### 6. Where does the data come from?

 The data is simulated in Python to generate mitai sales for an Indian Sweet Shop.

Hetal Kumbharana 
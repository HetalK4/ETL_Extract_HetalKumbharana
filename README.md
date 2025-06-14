## Project Title: ETL Extract and Transform Lab

This project carries out Full and Incremental Extraction as well as data transformation for an Indian Sweet Shop's dataset `mitai_sales_data`.

Hetal Kumbharana - 670207

### Contents

- `etl_extract.ipynb`: Jupyter Notebook that includes simulating synthetic data, Full and Incremental Extraction, transforming the full data and the incremental data.
- `last_extraction.txt`: Stores the latest extraction date and time.
- `mitai_sales_data.csv`: Simulated synthetic data.
- `initial_last_extraction_date.png`: Screenshot showing the *initial* last extraction date.
- `updated_last_extraction_date.pdg`: Screenshot showing the *updated* last extraction date.
- `transformed_full.csv`: Transformed *fully extracted* data.
- `transformed_incremental.csv`: Transformed *incrementally extracted* data.

### Description of what the notebook `etl_extract.ipynb` does:

1. Simulates synthetic mitai sales data for an Indian sweet shop for the months of November and December 2024.
2. Implements full extraction on the mitai sales data.
3. Implements incremental extraction since the last extraction date.
4. Updates `last_extraction.txt` to the most recent update time.
5. Transforms the fully extracted and incremetally extracted data by converting data types, handling missing values, removing duplicates, and categorizing the 'Amount'.

### Tools used:

Python, pandas, Jupyter

### How to reproduce:
- How to run the notebook:
  
        - Ensure you have `notebook` installed.
  
        - Open `etl_extract.ipynb`
  
        - Run the cells to display the output of the codes.

- *Where does the data come from?* The data is simulated in Python to generate mitai sales for an Indian Sweet Shop.

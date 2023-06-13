## Instructions:

1. Download directory to local drive
2. Run python -m pip install -r requirements.txt
3. Ensure sample_US_equity_close.csv is in same directory as pairs_selection_and_backtesting.ipynb
4. Run unsupervised_pairs_selection.ipynb

## File Structure:

-   "_Stocks in the SP 500 Index.csv_" | List of stocks in SP 500.
-   "_data_collection.ipynb_" | Prepares dataset for training. Takes list of stocks in SP500 and generates daily close values of said stocks from 2010-2022 and stores it in "_sample_US_equity_close.csv_".
-   "_sample_US_equity_close.csv_" | Dataset of daily close values from 2010-2022 of all stocks in SP500.
-   "_pairs_selection_and_backtesting.ipynb_" | Main Jupyter Notebook containing code for optimal pairs selection and backtesting.
-   " _mlpairs.py_" | Helper python library for conducting pairs selection based on paper.
-   "_requirements.txt_ "| List of python package requirements for this repo.

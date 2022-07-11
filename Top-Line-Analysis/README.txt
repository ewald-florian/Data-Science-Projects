README 
———————

Project includes to build a P&L statement and to conduct a top-line analysis to identify drivers of gross margin and EBITDA growth. The project has a strong focus on data cleaning and EDA. 

Files:


Top-Line-Analysis-Notebook.ipynb - The ipynb notebook contains the entire topline analysis. In order to use this notebook, please change directory. 

Dependencies used in the ipynb:
- pandas
- numpy
- matplotlib
- squarify
- plotly
- os


This two csv files will be generated when executing the notebook 
and are also already included in the folder:

gross_margin_all.csv - Csv file contains gross margins for all years and scopes. Used for comparison.
unnamed_accounts_all.csv - Csv file contains sum of transactions of unmapped Consolidation accounts.

Datasets used in the notebook:

AccountMapping.xlsx - Mapping file for PnL accounts via Account Numbers.
DATA_Cons.xlsx - Consolidation data.
DATA_SKU - Above margin level data.
Destinations.xlsx - Mapping file for delivery destination countries via Country ID.
Entities.xlsx - Mapping file for entity countries via Country ID

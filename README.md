# moneydemand

This repository contains the money demand database compiled as part of the 
OeNB Anniversary Fund Project No. 18692.

## Repository structure

- `money_demand_data_documentation.pdf`: Documentation of the database, 
including information on the variables, data sources, and data construction.

- `csv/`: Country- and frequency-specific CSV files named `cc_data_f.csv`, 
where `cc` is the lowercase two-letter country code and `f` indicates the 
data frequency:
  - `m`: monthly
  - `q`: quarterly
  - `a`: annual

- `xlsx/`: A consolidated Excel workbook named `moneydemand.xlsx`. Its worksheets 
are named `CC_F`, where `CC` is the uppercase two-letter country code and `F` 
indicates the data frequency:
  - `M`: monthly
  - `Q`: quarterly
  - `A`: annual
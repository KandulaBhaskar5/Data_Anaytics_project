# Data_Anaytics_project
# Dataset: State Transaction Data

## Description
This dataset contains records of transactions between different states, including details about the home and sale states, transaction counts, and time of transaction.

## File Information
- **Filename:** cb.csv
- **Total Rows:** 329
- **Total Columns:** 7

## Column Descriptions
1. **homestatecode** - Numerical code representing the home state.
2. **salestatecode** - Numerical code representing the sale state.
3. **month** - Month of the transaction.
4. **year** - Year of the transaction.
5. **txn_count** - Number of transactions recorded.
6. **salestatename** - Name of the sale state.
7. **homestatename** - Name of the home state.

## Data Characteristics
- The dataset consists of **numerical and categorical** values.
- `homestatecode` and `salestatecode` are **integer identifiers** for states.
- `month` and `year` represent the **time frame** of the transactions.
- `txn_count` represents the **number of transactions** between the states.
- `homestatename` and `salestatename` are **state names** corresponding to their codes.

## Usage
This dataset can be used for:
- Analyzing inter-state transaction trends.
- Identifying high-transaction volume states.
- Understanding seasonal variations in transactions.

## Notes
- Ensure to filter data by `year` and `month` for time-series analysis.
- Use `homestatecode` and `salestatecode` if mapping transactions to state codes.
- Data can be visualized using heatmaps or network graphs to represent state-wise transaction flow.


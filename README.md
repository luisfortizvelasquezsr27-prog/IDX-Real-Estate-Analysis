# IDX Real Estate Analysis

Data analysis pipeline for the IDX Exchange 12-Week Data Analyst Internship.
Analyzes CRMLS residential MLS transaction data using Python and Pandas.

## Notebooks

- **`data_loading.ipynb`** — Loads and concatenates monthly CRMLS CSV files, filters to Residential properties, and exports clean datasets.
- **`week_2_3_analysis.ipynb`** — Exploratory data analysis: missing value report, numeric distributions, and 30-year mortgage rate enrichment via FRED.

## How to Run

1. Place raw CRMLS CSV files in the same directory as the notebooks.
2. Run `data_loading.ipynb` first.
3. Then run `week_2_3_analysis.ipynb`.

## Dependencies

```bash
pip install pandas numpy matplotlib jupyter


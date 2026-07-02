IDX/
├── data/
│   └── raw/                          # CRMLSListing*.csv, CRMLSSold*.csv (gitignored)
│
├── output/
│   ├── listings_residential.csv      # produced by data_loading.ipynb (gitignored)
│   ├── sold_residential.csv
│   ├── listings_residential_with_rates.csv
│   └── sold_residential_with_rates.csv
│
├── notebooks/
│   ├── data_loading.ipynb            # Week 1 – load, concat, filter, save
│   └── week_2_3_analysis.ipynb       # Weeks 2–3 – EDA, distributions, FRED merge
│
├── scripts/                          # .py deliverables per the handbook
│   ├── week1_aggregate.py
│   ├── week2_3_eda.py
│   └── ...
│
├── .gitignore
└── README.md

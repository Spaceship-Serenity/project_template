# HC Analytics projects

## Project Folder Structure
```
├── README.md          <- The top-level README for analysts using this project.
│
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Code documentation, data dictionary, etc.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as Tableau dashboards, PPT, HTML etc.
│   └── figures        <- Generated graphics and figures to used in reporting.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment.
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data.
│   │   └── load_s0.sql
│   │
│   ├── transformation <- Scripts to transform raw data into features or metrics.
│   │   └── build_s1.sql
│   │
│   ├── analysis       <- Scripts to run analysis, build models, and optionally output final table
│   │   │                
│   │   ├── analysis.sql
│   │   └── predict_model.py
│   │
│   └── visualization  <- Scripts to create dashboard specific fields or dashboard specific calculations
│       └── visualize.py
│
└── test.py   <- code to run tests on analysis
```

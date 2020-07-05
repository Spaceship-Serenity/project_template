# HC Analytics projects

## Project Folder Structure
```
├── README.md          <- The top-level README for analysts using this project.
│
├── data
│   ├── s0            <- The original, immutable data dump.
│   ├── s1            <- Intermediate data that has been transformed.
│   └── z             <- The final, canonical data sets for modeling.
│
├── docs              <- Data dictionaries, manuals, and all other explanatory materials.
│   ├── data_dict           
│   │   ├── data_pipeline.md           <- explanation and image of final data pipeline produced
│   │   └── raw-data-dictionary.xlsx   <- html, excel, screenshot of raw data 
│   │
│   ├── data_reports
│   │   ├── dataset1_data_profile.html
│   │   └── dataset2_data_profile.html
│   │
│   ├── project <- Scripts to transform raw data into features or metrics.
│   │   ├── project_plan.md
│   │   ├── project_tasks.xlsx
│   │   └── requirements.ppt
│   │
│   ├── data_dictionary.dbml   <- writeup and details of table or set of tables produced by this project
│   ├── data_summary.md
│   └── project_summary.md
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`. 
│
├── reports            <- Generated analysis as Tableau dashboards, PPT, HTML etc.
│   └── figures        <- Generated graphics and figures to used in reporting.
│
└── code               <- Source code for use in this project.
    │
    ├── analysis       <- Scripts to run analysis, build models, and optionally output final table
    │   │                
    │   ├── analysis.sql
    │   └── predict_model.py
    │
    ├── data                <- Scripts to download or generate data.
    │   └── load_s0.sql
    │
    ├── transformation      <- Scripts to transform raw data into features or metrics.
    │   └── build_s1.sql
    │
    ├── visualization       <- Scripts to create dashboard specific fields or dashboard specific calculations
    │   └── visualize.py
    │
    ├── requirements.txt    <- The requirements file for reproducing the analysis environment.
    └── test.py             <- code to run tests on analysis
```

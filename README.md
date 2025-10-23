# FlightDelays

## Quickstart (inside repo)
```bash
# 1) Clone the repo
git clone https://github.com/AllanWTham/FlightDelays.git
cd FlightDelays

# 2) Ensure Git LFS pointers are pulled as real files
git lfs install
git lfs pull

# 3) To run the Jupyter notebook, use 'onpremises.ipynb' contained in the 'notebook' directory
cd notebooks

# 4) This notebook contains the following steps:
1. Problem framing & data scope

  - Step 1: Problem formulation and data collection: 
    (a) decide why ML is appropriate
    (b) define the business problem, success metrics and desired ML output
    (c) identify the ML problem type (binary classification).

2. Setup
  - Environment and libraries section (“Setup”) to get the notebook ready.

3. Data preprocessing & EDA
  - Step 2: Data preprocessing and visualization with guidance to load data, inspect schema/types, compute basic statistics and examine target distribution.

4. Model training & initial evaluation
  - Step 3: Model training and evaluation — train/test split, baseline logistic regression and evaluate via confusion matrix, ROC and metrics (accuracy, precision, recall, sensitivity/specificity).

5. Iteration & feature engineering
  - Iteration II
  - Step 5: Feature engineering — address class balance, correlated features, dimensionality reduction, adding external data and compare performance after changes.

6. Visualization & communication
  - Step 6: Using Tableau +  Data Preparation for Tableau Visualization — prepare aggregated outputs and build/share a dashboard to communicate insights.

7. Wrap-up
  - Conclusion — reflect on iterations, results and next steps.

# 5) After the execution, the root directory will contain the following structure:
.
├── data
│   ├── Output_CSV
│   │   ├── daily-summaries.csv
│   │   ├── FinalProject_combined_csv_v1.csv
│   │   ├── FinalProject_combined_csv_v2.csv
│   │   ├── FinalProject_combined_files.csv
│   │   └── FinalProject__FlightDelay_Tableau.csv
│   ├── readme.html
│   └── Source_CSV
│       ├── On_Time_Reporting_Carrier_On_Time_Performance_(1987_present)_2014_10.csv
│       ├── On_Time_Reporting_Carrier_On_Time_Performance_(1987_present)_2014_11.csv
│       ├── ...
│       └── On_Time_Reporting_Carrier_On_Time_Performance_(1987_present)_2018_9.csv
├── data_zipped
│   ├── On_Time_Reporting_Carrier_On_Time_Performance_1987_present_2014_10.zip
│   ├── On_Time_Reporting_Carrier_On_Time_Performance_1987_present_2014_11.zip
│   ├── ...
│   └── On_Time_Reporting_Carrier_On_Time_Performance_1987_present_2018_9.zip
├── FlightDelays
│   ├── notebooks
│   │   └── onpremises.ipynb
│   └── README.md
├── FlightDelays.twb
└── onpremises.ipynb
```

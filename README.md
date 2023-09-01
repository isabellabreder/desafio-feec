# How this problem resolution was thinked

### 1. Build csv  
The `build_csv.ipynb` file transforms the structured .mat file (batch1.mat) into a pandas DataFrame, and then exports it to .csv files (b1c[0...4]_summary.csv).  

### 2. Data cleaning
The `data_cleaning.ipynb` treats the missing values and outliers.

### 3. Feature engineering
`feature_engineering.csv` tries to dig for features that can be helpful for the data.

### 4. Clustering 
`clustering.ipynb` applies a clustering algorithm to the data, trying to build clusters and find out tendencies.
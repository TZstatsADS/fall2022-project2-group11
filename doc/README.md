# Dataset Cleaning and ETL Analysis

### Goals:
1. Giving a general look of the dataset, and then running Sanity Check towards NYCLink_location and NYCLink_usage to find out any missing values and outliers
2. Convert datetime-like string to datetime, and usage time (format %H:%M:%S) to datetime so that we could analyze the trending of numeric value over the time period
3. Removing features that are irrelevant to our analysis and also adding new features that will contribute to our furthur analysis
4. Step 2 and Step 3 contribute to ease the future feature engineering process if we would like to run any machine learning models towards our dataset.
5. ETL Analysis and Visualization i.e. the number of NYCLink installed over time and the number of NYCLink activated over time; also including the number of NYCLink installed over different regions

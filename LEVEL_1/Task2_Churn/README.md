# Level 1 - Task 2: Exploratory Data Analysis (EDA)

## Objective
Perform Exploratory Data Analysis on the Customer Churn dataset to understand data distribution, detect patterns, and find correlations.

## Dataset
**File**: `churn-bigml-20.csv`  
This dataset contains customer information used to analyze churn behavior.

 Tools Used
- Python
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

Tasks Completed
1. **Summary Statistics**  
   Calculated mean, median, mode, standard deviation for numerical columns.

2. **Data Visualization**
   - `histogram_day_minutes.png`: Distribution of Day Minutes
   - `boxplot_day_minutes.png`: Outlier detection for Day Minutes
   - `scatter_day_minutes_charge.png`: Relationship between Day Minutes and Day Charge
   - `correlation_heatmap.png`: Correlation matrix between features

3. **Insights**
   - Identified data distribution and outliers
   - Found relationships between key features
   - Visualized correlations to guide further analysis

 Files in this folder
- `churn-bigml-20.csv` - Raw dataset
- `cleaned data.ipynb` - Notebook with all EDA code and analysis
- `*.png` - 4 visualization plots generated during EDA

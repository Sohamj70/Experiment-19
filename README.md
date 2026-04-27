# Aim : Real World and Interactive Visualizations
# Theory
Data cleaning and statistical analysis are fundamental steps in data science. Raw data often contains inconsistencies such as missing values, duplicate records, and incorrect formats. Data cleaning ensures that the dataset becomes accurate, consistent, and usable.
Statistical analysis helps summarize and interpret the data using measures like mean, median, standard deviation, and distribution patterns. Python libraries such as pandas and numpy provide efficient tools to perform these operations.

### Functions and Commands Used
1. Importing Libraries
- import pandas as pd → Data manipulation and analysis
- import numpy as np → Numerical computations

2. Loading Dataset
- pd.read_csv("file.csv") → Loads dataset into a DataFrame

3. Data Inspection
- df.head() → First 5 rows
- df.tail() → Last 5 rows
- df.shape → Number of rows and columns
- df.size → Total elements
- df.info() → Data types and non-null values

4. Checking Missing Values
- df.isnull() → Detect missing values
- df.isnull().sum() → Count missing values

5. Handling Missing Values
- df.fillna(value) → Replace missing values
- df.dropna() → Remove rows with missing values

6. Handling Duplicates
- df.duplicated().sum() → Count duplicates
- df.drop_duplicates() → Remove duplicates

7. Statistical Analysis
- df.describe() → Summary statistics
- df.mean() → Mean
- df.median() → Median
- df.std() → Standard deviation
- df.min() / df.max() → Min and Max values

8. Data Selection and Filtering
- df['column'] → Select column
- df.loc[] → Conditional selection
- df[df['column'] > value] → Filtering

9. Sorting Data
- df.sort_values(by='column') → Sort data
- ascending=False → Descending order

10. Value Analysis
- df['column'].value_counts() → Frequency count
- df['column'].nunique() → Unique count
- df['column'].unique() → List unique values
- Key Operations Performed
- Loaded and explored the dataset
- Identified and handled missing values
- Removed duplicate records
- Performed statistical analysis (mean, median, standard deviation)
- Filtered and sorted data
- Analyzed value distribution
# Conclusion
Data cleaning and statistical analysis help in improving the quality and reliability of data. Using Python libraries like pandas and numpy, we can efficiently preprocess data and extract meaningful insights. This experiment demonstrates how raw data can be cleaned and analyzed to support better decision-making.
Data cleaning and statistical analysis significantly improve data quality and reliability. Using Python libraries like pandas and numpy, raw data can be efficiently processed and transformed into meaningful insights. This process enables better understanding of data patterns and supports informed decision-making.

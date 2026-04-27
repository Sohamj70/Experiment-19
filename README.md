# Experiment-19: Data Analysis and Visualization using Pandas
# Aim:
To perform data analysis using Pandas and visualize insights using Matplotlib and Seaborn.
# Theory:
Data analysis involves inspecting, cleaning, transforming, and modeling data to discover useful information and support decision-making.
1). Pandas - is a powerful Python library used for:
- Data manipulation
- Data cleaning
- Statistical analysis
- Data Visualization
- Visualization helps in:
- Identifying trends
- Understanding relationships
- Detecting outliers
## Functions used:
- DataFrame – Tabular data structure in Pandas
- Data Cleaning – Handling missing or incorrect values
- Descriptive Statistics – Mean, median, standard deviation
- Grouping Data – Using groupby()
- Visualization – Graphical representation of data
# Commands and Code Explanation
1. Importing Libraries
- pd: Data handling
- np: Numerical operations
- plt: Plotting graphs
- sns: Advanced visualization
2. Loading Dataset
- df = pd.read_csv("data.csv")
- Reads CSV file into DataFrame
3. Displaying Data
- head() → shows first 5 rows
- info() → structure of dataset
- describe() → statistical summary
4. Handling Missing Values
- df.isnull().sum()
- df.dropna()
- df.fillna(method='ffill')
- Checks and handles missing data
5. Selecting Data
- Access specific rows and columns
6. Filtering Data
- Filters rows based on condition
7. Grouping Data
- Groups data and calculates mean
8. Sorting Data
- Sorts dataset

# Conclusion:
In this experiment, data analysis was performed using Pandas, including data cleaning, filtering, grouping,
and statistical analysis. Various visualization techniques using Matplotlib and Seaborn were implemented to better

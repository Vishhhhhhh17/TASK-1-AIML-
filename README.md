# TASK-1-AIML-

Data Cleaning & Preprocessing – Titanic Dataset

Steps Performed :

1.Imported the Dataset

2.Loaded the Titanic CSV file using pandas.

3.Explored the dataset to understand data types and missing values.

4.Handled Missing Values

5.Dropped the Cabin column due to too many missing values.

6.Filled missing values in Age with the median.

7.Filled missing values in Embarked with the mode (most frequent value).

8.Encoded Categorical Variables

9.Converted Sex column using label encoding (male → 0, female → 1).

10.Applied one-hot encoding to the Embarked column.

11.Dropped Unnecessary Columns

12.Removed Name and Ticket columns, as they are not relevant for ML models.

13.Standardized Numerical Features

14.Used StandardScaler to standardize Age and Fare so they have mean 0 and standard deviation 

15.Detected and Removed Outliers

16.Used boxplots to visualize outliers in the Fare column.

17.Removed outliers using the IQR (Interquartile Range) method.


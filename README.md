# TASK-1-AIML-

Data Cleaning & Preprocessing – Titanic Dataset
Objective
Prepare the Titanic dataset for Machine Learning by cleaning, transforming, and standardizing the data.

Steps Performed
Imported the Dataset

Loaded the Titanic CSV file using pandas.

Explored the dataset to understand data types and missing values.

Handled Missing Values

Dropped the Cabin column due to too many missing values.

Filled missing values in Age with the median.

Filled missing values in Embarked with the mode (most frequent value).

Encoded Categorical Variables

Converted Sex column using label encoding (male → 0, female → 1).

Applied one-hot encoding to the Embarked column.

Dropped Unnecessary Columns

Removed Name and Ticket columns, as they are not relevant for ML models.

Standardized Numerical Features

Used StandardScaler to standardize Age and Fare so they have mean 0 and standard deviation 1.

Detected and Removed Outliers

Used boxplots to visualize outliers in the Fare column.

Removed outliers using the IQR (Interquartile Range) method.


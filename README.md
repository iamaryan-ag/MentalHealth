# Mental Health Tracker

This repository contains a Python script that performs data analysis and builds a linear regression model using the `pandas`, `numpy`, `seaborn`, `matplotlib.pyplot`, and `plotly.express` libraries.

## Prerequisites

Make sure you have the following dependencies installed:

- pandas
- numpy
- seaborn
- matplotlib
- plotly
- scikit-learn

You can install the required packages by running the following command:

```
pip install pandas numpy seaborn matplotlib plotly scikit-learn
```

## Usage

1. Clone this repository or download the script file: `Mental Health Tracker.ipynb`.

2. Make sure you have the following CSV files in the same directory as the script:

   - `mental-and-substance-use-as-share-of-disease.csv`
   - `prevalence-by-mental-and-substance-use-disorder.csv`

3. Open the terminal or command prompt and navigate to the directory containing the script.

4. Run the script using Jupyter Notebook

5. The script will perform data analysis, merge the datasets, visualize correlations, and build a linear regression model.

6. The script will display the model's performance metrics for both the training set and testing set.

Note: The script uses the `warnings` module to suppress warnings and enhance readability.

## File Description

- `Mental Health Tracker.ipynb`: Python script that performs data analysis and builds a linear regression model.
- `mental-and-substance-use-as-share-of-disease.csv`: CSV file containing data for mental and substance use as a share of disease.
- `prevalence-by-mental-and-substance-use-disorder.csv`: CSV file containing data for prevalence by mental and substance use disorder.

## Results

The script performs the following steps:

1. Imports necessary libraries and suppresses warnings.

2. Reads and preprocesses the first dataset (`mental-and-substance-use-as-share-of-disease.csv`).

3. Performs data analysis on the first dataset, including descriptive statistics and data type information.

4. Reads and preprocesses the second dataset (`prevalence-by-mental-and-substance-use-disorder.csv`).

5. Performs data analysis on the second dataset, including descriptive statistics and data type information.

6. Merges both datasets into one based on a common key.

7. Sets appropriate column names for better readability.

8. Visualizes the correlations between variables using a heatmap.

9. Plots the relationship between mental health indicators (`Eating disorder` and `Anxiety`) and the target variable (`DALY`).

10. Encodes categorical variables using LabelEncoder.

11. Splits the dataset into training and testing sets.

12. Builds a linear regression model using the training data.

13. Evaluates the model's performance on both the training set and testing set, calculating metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared score.

The script provides insights into the dataset and builds a linear regression model to predict the `DALY` (Disability-Adjusted Life Years) based on the available features.

# Swedish Insurance Analysis

This project analyzes the Swedish Insurance dataset using simple linear regression techniques. The analysis includes data exploration, statistical calculations, coefficient estimation, and prediction visualization.

## Dataset

The dataset used in this project is the Swedish Insurance dataset, which contains information about the number of claims (X) and the total payment for all claims (Y) in thousands of Swedish Kronor for different geographical zones.

## Project Structure

The project consists of the following main steps:

1. Data Loading and Exploration
2. Statistical Analysis
3. Linear Regression Modeling
4. Prediction and Visualization

## Requirements

To run this project, you'll need the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib

You can install these libraries using pip:

```
pip install pandas numpy seaborn matplotlib
```

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/HuzaifaXool/swedish-insurance-analysis.git
   cd swedish-insurance-analysis
   ```

2. Ensure you have the `swedish_insurance.csv` file in the project directory.

3. Run the Jupyter notebook or Python script to perform the analysis.

## Analysis Steps

### 1. Data Loading and Exploration

- Load the dataset into a Pandas DataFrame
- Display the first 10 rows of the dataset
- Visualize the data using box plots and scatter plots

### 2. Statistical Analysis

- Calculate mean and variance for both the number of claims (X) and the total payment (Y)
- Calculate covariance between X and Y

### 3. Linear Regression Modeling

- Estimate coefficients b0 (intercept) and b1 (slope) for the simple linear regression model
- Make predictions using the estimated coefficients

### 4. Prediction and Visualization

- Compare predicted values (Y_hat) with actual values (Y)
- Plot original data points and the regression line for visual comparison

## Results

The analysis provides insights into the relationship between the number of claims and the total payment in the Swedish Insurance dataset. The README file can be updated with key findings and observations once the analysis is complete.


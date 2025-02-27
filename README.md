# Exploratory Analysis on Used Cars

## Objectives

* Explore features or characteristics to predict the price of a car
* Analyze patterns and run descriptive statistical analysis
* Group data based on identified parameters and create pivot tables
* Identify the effect of independent attributes on the price of cars

## Structure

<div class="alert alert-block alert-info" style="margin-top: 20px">
<ol>
    <li><a href='#Import-Data-from-Module-2'>Import Data from Module</a></li>
    <li><a href='#Analyzing-Individual-Feature-Patterns-Using-Visualization'>Analyzing Individual Feature Patterns using Visualization</a></li>
    <li><a href='#Descriptive-Statistical-Analysis'>Descriptive Statistical Analysis</a></li>
    <li><a href='#Basics-of-Grouping'>Basics of Grouping</a></li>
    <li><a href='#Correlation-and-Causation'>Correlation and Causation</a></li>
</ol>
</div>

<hr>

## Files

- `usedcars.csv`: Dataset containing information about used cars.
- `Exploratory_data_analysis_cars.ipynb`: Jupyter notebook containing the exploratory data analysis.

## Usage

1. **Import Data**: The data is imported from a CSV file using the `pandas` library.
    ```python
    import pandas as pd
    df = pd.read_csv("usedcars.csv", header=0)
    ```

2. **Analyze Individual Feature Patterns using Visualization**: Visualize different features to understand their distribution and relationship with the car price.

3. **Descriptive Statistical Analysis**: Perform descriptive statistical analysis to summarize the main features of the dataset.

4. **Basics of Grouping**: Group data based on different categories and perform analysis on the individual groups.
    ```python
    df['drive-wheels'].unique()
    ```

5. **Correlation and Causation**: Identify the correlation between different features and the car price to understand causation.

## Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `requests`

Install the dependencies using:
```sh
pip install pandas numpy matplotlib seaborn requests
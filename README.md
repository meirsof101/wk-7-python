
# Iris Dataset Analysis and Visualization

## Project Overview
This project explores the famous Iris dataset through data analysis and visualization techniques using Python. The analysis includes data exploration, statistical analysis, and creating various visualizations to understand the patterns and relationships within the dataset.

## Dataset
The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains measurements of 150 iris flowers from three different species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

For each flower, the following features are measured (in centimeters):
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Tasks Completed

### Task 1: Data Loading and Exploration
- Loaded the Iris dataset using pandas
- Displayed the first few rows to inspect the data structure
- Examined data types and checked for missing values
- Cleaned the dataset (handled missing values where necessary)

### Task 2: Basic Data Analysis
- Computed basic statistics (mean, median, standard deviation, etc.) for numerical columns
- Performed grouping by species and analyzed the mean of each measurement
- Identified patterns and key differences between the three iris species

### Task 3: Data Visualization
Created multiple visualizations to analyze the dataset:

1. **Line Chart**: Visualized trends in measurements across different species
   - Shows how mean measurements vary across species
   - Highlights the significant differences in petal dimensions between species

2. **Bar Chart**: Compared average petal length across species
   - Clearly demonstrates that Iris Virginica has the longest petals
   - Iris Setosa has distinctly shorter petals than the other species

3. **Histogram**: Analyzed the distribution of sepal width
   - Revealed the frequency distribution and range of sepal widths
   - Identified the most common sepal width measurements

4. **Scatter Plot**: Explored the relationship between sepal length and petal length
   - Demonstrated strong correlation between these measurements
   - Showed clear clustering by species
  
## Key Findings

1. **Species Differentiation**:
   - Iris Setosa is clearly distinguishable from the other two species based on petal dimensions
   - Versicolor and Virginica show some overlap but can be separated by combined features

2. **Feature Relationships**:
   - Strong positive correlation between petal length and petal width (r = 0.96)
   - Moderate positive correlation between sepal length and petal measurements
   - Negative correlation between sepal width and other measurements

3. **Data Distribution**:
   - Most measurements follow approximately normal distributions within each species
   - Some measurements show bimodal distribution when all species are combined
   - Few outliers detected, suggesting clean and consistent data collection

n

## How to Run
1. Ensure you have Python installed with the required libraries
2. Download the Jupyter notebook and Iris.csv file
3. Run the notebook cells sequentially to reproduce the analysis and visualizations

## Future Work
- Apply machine learning algorithms to predict species based on measurements
- Expand the analysis with additional flower datasets for comparison
- Implement interactive visualizations for deeper exploration

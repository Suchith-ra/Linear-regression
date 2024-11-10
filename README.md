# Linear Regression Analysis: Predicting Student Scores Based on Study Hours

## Project Overview
This project focuses on predicting student scores based on the number of hours they study, using **Linear Regression**, a basic yet powerful Supervised Machine Learning technique. The primary goal is to build a simple linear regression model to explore and understand the relationship between hours studied and scores achieved.

## Project Structure
1. **Data Loading and Exploration**: The dataset is loaded and examined for an initial understanding of the relationship between hours studied and scores obtained.
2. **Data Visualization**: A scatter plot visualizes the correlation between study hours and scores, helping to identify a potential linear relationship.
3. **Linear Regression Coefficients Calculation**: The slope and intercept for the regression line are calculated using the least squares method.
4. **Model Visualization**: A regression line is plotted over the scatter plot, allowing a visual assessment of how well the model fits the data points.
5. **Model Evaluation**: The model’s accuracy is evaluated by calculating the \( R^2 \) score, which indicates how well the regression line represents the data.
6. **Prediction**: The model is used to predict scores based on a specified number of study hours, demonstrating its applicability in forecasting new values.

## Dataset
The project uses a simple dataset named `student_scores.csv`, which contains two columns:
- **Hours**: Represents the number of hours a student studied.
- **Scores**: Represents the scores achieved by the student.

## Requirements
To run this project, the following Python libraries are required:
- **NumPy**: Used for mathematical operations and array handling.
- **Pandas**: Used for data loading, manipulation, and analysis.
- **Matplotlib**: Used for data visualization, including scatter plots and regression lines.

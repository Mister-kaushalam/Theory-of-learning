
# Theory of Learning
## Understanding Hoeffding bound, perceptrons and learning curves.

This repository contains the implementation of tasks related to the Theory of Learning. The project showcases concepts such as perceptron classification, learning curves, linear regression, and linear classification, demonstrating the application of theoretical knowledge in practical scenarios.

## Project Description

The tasks are aimed at understanding the foundational principles of learning models, their behavior with various datasets, and how loss/error functions affect performance. 

We'll:
   1. Summarise my Understanding of how Hoeffding bound, shattering, break points, growth function inform VC bound
   2. Understand approximation genralization of a model in terms of complexity, bias and variance of a model, and the resulting under/overfitting fiven the available data.

The repository is structured to highlight the following:

### Task 1: Perceptron and Classification
- **Objective**: Describe how a perceptron can classify objects based on linear separability.
- **Key Concepts**:
  - Input Space and Output Space
  - Unknown Target Function
  - Hypothesis Set and Final Hypothesis
  - Error Measures: In-sample (Ein) and Out-of-sample (Eout)

### Task 2: Learning Curves
- **Objective**: Analyze learning curves to understand the relationship between training and test errors as the number of data points increases. Plotted learning curves of logistic regression and Neural Network (Basic MLP Classifier).
- **Key Observations**:
  - Training error vs. test error
  - Impact of sample size on error
  - Complexity of models

### Task 3: Impact of Loss/Error Functions
- Implemented linear regression using the dataset `Et1_Task3a.csv`.
- Added functionality to compute error functions.
- Visualized regression lines and examined the impact of outliers.
- Addressed questions related to error contribution and suitability of the squared error measure.

## Modifications and Enhancements
- **Enhanced Visualization**: Added plots to better illustrate decision boundaries and regression lines.
- **Code Optimization**: Structured the code for modularity and readability.
- **Extended Analysis**: Provided detailed discussions and answers to all assigned questions, incorporating real-world implications.

## Repository Structure
- **Notebook**: [Theory of Learning.ipynb](Theory of Learning.ipynb) - Contains all tasks with code, markdown explanations, and visualizations.
- **Data**: Ensure datasets `Et1_Task3a.csv` and `Et1_Task2.csv` are in the same directory for the notebook to run seamlessly.
- **Readme**: This file provides an overview of the project.


## Results and Discussions
- **Task 1**: Detailed markdown explanation of perceptron classification concepts.
- **Task 2**: Analysis of learning curves and error metrics.
- **Task 3**: Implementations of linear regression and classification with visualizations and insights.

## Key Learnings
- Understanding the theoretical underpinnings of learning models.
- Practical implications of error functions and their suitability for different tasks.
- Effect of outliers on regression and classification models.



For any questions or discussions, feel free to raise an issue or reach out!

# Salary Prediction Using Regression Models

## **Overview**

This project aims to build and evaluate regression models to predict the salary of employees based on their job level. The dataset includes job titles, corresponding levels, and salaries, which are used to create models that can estimate salaries for new employees based on their job levels.

### **Dataset**

The dataset used for this project is `Position_Salaries.csv` and contains the following columns:

- **Position**: Job title of the employee.
- **Level**: Numerical level associated with the position.
- **Salary**: Annual salary of the employee.

**Example data:**

| Position         | Level | Salary    |
|------------------|-------|-----------|
| Business Analyst | 1     | 45000     |
| Junior Consultant| 2     | 50000     |
| Senior Consultant| 3     | 60000     |
| Manager          | 4     | 80000     |
| Country Manager  | 5     | 110000    |
| Region Manager   | 6     | 150000    |
| Partner          | 7     | 200000    |
| Senior Partner   | 8     | 300000    |
| C-level          | 9     | 500000    |
| CEO              | 10    | 1000000   |

## **Project Objective**

The objective of this project is to predict the salary of a new employee based on their job level using both Linear Regression and Polynomial Regression models. For instance, if a new employee has a job level of 6.5, the goal is to estimate an appropriate salary offer.

## **Project Files**

- **Data/**: Contains the `Position_Salaries.csv` file used in the project.
- **Notebooks/**: Jupyter notebooks with the analysis and model implementation.
  - `Linear_Regression.ipynb`: Contains code and analysis for Linear Regression.
  - `Polynomial_Regression.ipynb`: Contains code and analysis for Polynomial Regression.
- **Reports/**: Includes reports and visualizations.
  - `Linear_Regression_Report.html`: HTML report for the Linear Regression model.
  - `Polynomial_Regression_Report.html`: HTML report for the Polynomial Regression model.
- **Presentations/**: Contains presentation slides summarizing the project.
  - `Salary_Prediction_Presentation.pptx`: PowerPoint presentation with the project overview and results.

## **Installation and Setup**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/salary-prediction-regression.git

## **Results**

**Linear Regression Model:** This model provides a basic linear estimate of salary based on job level. It is useful for understanding simple relationships between job level and salary, but may not capture complex patterns.

**Polynomial Regression Model:** This model uses a polynomial equation to provide a more flexible fit to the data. It captures complex relationships and can better estimate salaries for job levels that are not well represented by a linear model.

**Performance Metrics:** Both models are evaluated based on Mean Squared Error (MSE) and visualized through scatter plots with trendlines. The Polynomial Regression model generally provides a better fit for the data, as it accounts for non-linear trends.

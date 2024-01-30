# Mixed_Integer_Quadratic_Programming_for_Variable_Selection

## Project Overview
This project explores the use of Mixed Integer Quadratic Programming (MIQP) for direct variable selection in regression analysis. We aim to compare MIQP with LASSO regression to evaluate the effectiveness of variable selection and shrinkage in predictive modeling. The project leverages advancements in optimization software to solve MIQP problems and gain insights into variable importance in regression models.

## Methodology
1. MIQP Formulation: Utilizing Gurobi optimizer in Python to solve the MIQP model for variable selection in regression.
2. LASSO Regression: Implementing LASSO regression using scikit-learn to compare with MIQP results.
3. Data Analysis: Conducting 10-fold cross-validation on training data, followed by predictions on test data.
4. Optimization and Computational Efficiency: Assessing the computational trade-offs between MIQP and LASSO for direct variable selection.

## Key Components
1. Variable Selection: Identifying the most significant variables in regression models using MIQP.
2. Model Comparison: Evaluating the performance of MIQP against LASSO in terms of variable selection and prediction accuracy.
3. Computational Analysis: Analyzing the computational efficiency and scalability of MIQP in solving complex regression problems.

## Technologies Used
1. Python for data analysis and model implementation.
2. Gurobi optimizer for solving MIQP problems.
3. Scikit-learn for LASSO regression implementation.

## Conclusion
The project aims to provide insights into the efficiency and effectiveness of MIQP in variable selection, offering a comparative analysis with LASSO regression. It demonstrates the potential of MIQP in enhancing predictive analytics and variable selection methodologies.

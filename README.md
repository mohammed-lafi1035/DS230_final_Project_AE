
DS230 Final Project: Instacart Market Basket Analysis
Project Overview
This project is a comprehensive machine learning walkthrough aimed at predicting user shopping behavior using the Instacart dataset. We address two main predictive tasks:   



Task A (Classification): Predicting whether a (user, product) pair will be reordered in the next order.   



Task B (Regression): Predicting the days until the next order (or reorder count).   

Key Features


Full EDA & Preprocessing: Memory-optimized data ingestion, missing value analysis, and seasonal trend visualization.   



Feature Engineering: Implementation of user-level, product-level, and user-product interaction statistics.   



Model Suite: Comparison of various models including Logistic Regression, SVM, Random Forest, and Gradient Boosting (XGBoost/LightGBM).   


Explainability: Model interpretations using SHAP values and partial dependence plots.   



Robustness Testing: Stress tests using Gaussian noise and outlier injection to evaluate model stability.   

Repository Structure


notebooks/: Modular Jupyter notebooks for EDA, Feature Engineering, and Modeling.   



src/: Python scripts for data cleaning and utility functions.   



dashboard/: Interactive Plotly/Streamlit dashboard.   


reports/: Final project report in PDF format.   



requirements.txt: List of dependencies for reproducibility.   

How to Run
Clone the repository.

Install dependencies: pip install -r requirements.txt.   

Run the notebooks in the notebooks/ directory sequentially.

Team Members & Workload Distribution


[mohammed lafi ]: EDA, Preprocessing, and Task A Modeling, Feature Engineering, SHAP Explainability, Final Report.   60%



[abdulkareem alshayeb]: Feature Engineering, Task B Modeling, and Robustness Testing, Dashboard Development.   40&



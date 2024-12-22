
Handset Price Prediction Project
Overview
This project aims to predict handset prices based on their features and analyze the key factors that influence pricing. By utilizing machine learning models, the project provides actionable insights to guide pricing and marketing strategies in a competitive market.

Project Structure
data/: Contains the dataset used for training and testing the models.
notebooks/: Jupyter notebooks with step-by-step analysis, preprocessing, and modeling.
src/: Python scripts for data preprocessing, feature selection, and model training.
reports/: Generated outputs, including visualizations and summary reports.
Handset_Price_Prediction_Presentation.pptx: A PowerPoint presentation summarizing the project's findings and recommendations.
Steps and Methodology
Data Exploration:

Analyzed the structure of the dataset.
Identified missing values, outliers, and inconsistencies.
Visualized feature distributions and correlations.
Data Preprocessing:

Handled missing data using imputation.
Detected and removed outliers.
Encoded categorical variables (e.g., handset model, processor).
Scaled numerical features for consistency.
Feature Analysis:

Conducted correlation analysis and feature selection.
Identified key features (e.g., memory, camera, battery) influencing handset prices.
Model Building:

Trained multiple models, including Random Forest and XGBoost.
Tuned hyperparameters for optimized performance.
Selected the best-performing model based on evaluation metrics.
Model Evaluation:

Used metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score to evaluate models.
Compared actual and predicted prices to assess accuracy.
Insights and Recommendations:

Highlighted the importance of features like memory and camera in pricing.
Recommended strategies for pricing and marketing based on model results.
Key Findings
Memory, battery capacity, and camera resolution were the most critical factors influencing handset prices.
The Random Forest model provided reliable performance, with XGBoost showing potential for further optimization.
Technologies Used
Languages: Python
Libraries:
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn, XGBoost
Tools:
Jupyter Notebook
PowerPoint for reporting and presentation

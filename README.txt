Climate Change Impact on Agriculture: A Machine Learning Approach

Overview
--------
This project analyzes the impact of climate change on agriculture, focusing on how rising temperatures and changing precipitation patterns affect crop yields and soil health. Machine learning models are developed to predict agricultural outcomes and evaluate adaptive farming strategies.

Objectives
----------
- Analyze the relationship between climate variables (e.g., temperature, precipitation) and agricultural productivity.
- Develop machine learning models to predict crop yields and soil health.
- Identify effective adaptive farming strategies to mitigate climate impacts.

Dataset
-------
- Source: Kaggle
- Time Period: 1990–2024
- Features:
  - Climate variables: Average Temperature, Precipitation, CO2 Emissions.
  - Agricultural factors: Soil Health Index, Crop Yield, Fertilizer Use.

Methodology
-----------
1. Data Collection & Preparation: Handled missing values and standardized features.
2. Exploratory Data Analysis: Conducted statistical analyses and visualizations, including correlation heatmaps and temperature binning.
3. Feature Engineering: Created features like Temperature Anomaly to improve model performance.
4. Model Development: Trained three models:
   - Linear Regression
   - Decision Tree
   - Gradient Boosting
5. Evaluation: Gradient Boosting outperformed other models with RMSE = 0.846 and R^2 = 0.322.

Results
-------
- Key Finding: Gradient Boosting is the most accurate model for predicting crop yields and soil health.
- Impact: Adaptive strategies like crop rotation and water management significantly improve agricultural resilience.

Installation
------------
1. Clone the repository:
   git clone https://github.com/your-repo-name.git
2. Install dependencies:
   pip install -r requirements.txt

Usage
-----
1. Load the dataset:
   df = load_dataset('path_to_dataset.csv')
2. Perform EDA:
   perform_eda(df)
3. Train models:
   models = train_models(X, y)
4. Evaluate results:
   evaluate_models(models, X_test, y_test)

Tools and Libraries
-------------------
- Python: Pandas, NumPy, Matplotlib, Seaborn
- Machine Learning: Scikit-learn

Contribution
------------
Feel free to fork the repository, open issues, or submit pull requests for improvements.

License
-------
This project is licensed under the MIT License.

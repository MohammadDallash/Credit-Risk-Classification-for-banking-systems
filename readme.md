# Credit Risk Classification for Banking Systems

## Project Overview
Developed a credit risk classification model using a dataset with mixed categorical and numerical features, incorporating a cost matrix for the business-specific outcomes.

## Key Steps

1. **Data Exploration and Visualization**
   - Explored data to understand distributions, correlations, and patterns.
   - Visualized data using plots and charts to identify trends and anomalies.

2. **Data Preprocessing**
   - Detected outliers and handled corrupted data.
   - Performed statistical analysis.
   - Applied minority class upsampling to address imbalance.

3. **Dimensionality Reduction**
   - Utilized Factor Analysis of Mixed Data (FAMD) to reduce feature complexity from 58 to 10, while maintaining model performance (F1-Score = 8.5).

4. **Model Training and Optimization**
   - Trained and optimized various algorithms:
     - XGBoost
     - RandomForest
     - KNN
     - Gaussian Naive Bayes
     - LightGBM
   - Used grid search for hyperparameter tuning.
   - Evaluated model generalization using k-fold cross-validation.
   - Monitored memory and time usage across classifiers.

## Summary
This project successfully developed a robust and efficient credit risk classification model tailored for banking applications, ensuring high performance and alignment with business-specific outcomes.

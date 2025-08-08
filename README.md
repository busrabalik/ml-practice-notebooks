
# ML Practice Notebooks
This repo has simple and clear projects and lesson notes I made while learning machine learning (ML).  
My goal is to leave a "recipe book" that I can use in the future and also help people who want to start ML projects.

# Water Potability Prediction

This project uses machine learning to check if water is safe to drink (**potable**) or not.  
The data comes from the `water_potability.csv` [https://www.kaggle.com/datasets/adityakadiwal/water-potability] file, which has chemical and physical properties of water samples.
**Main Steps:**
1. Look at the data (pie chart, correlation heatmap, missing values)
2. Fix missing values (fill with average values for each class)
3. Scale the data (min-max normalization)
4. Train models (Decision Tree, Random Forest)
5. Compare models (precision score, confusion matrix)
6. Tune the best model (Random Forest with RandomizedSearchCV)


# Heart Attack Prediction

This project uses machine learning to predict the risk of a heart attack.  
The data comes from the `heart.csv` [https://www.kaggle.com/datasets/sonialikhan/heart-attack-analysis-and-prediction-dataset] file, which contains medical and lifestyle information about patients.
**Main Steps:**
1. Look at the data (bar charts, heatmap, pair plots)
2. Check and handle missing values
3. Scale the data (min-max normalization)
4. Train models (Logistic Regression, Decision Tree, Random Forest)
5. Compare models (accuracy score, confusion matrix, classification report)
6. Tune the best model (Random Forest with RandomizedSearchCV)


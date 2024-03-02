# RateMe
Book rating ML project 

Project management with poetry for dependencies
pip install poetry 

Purpose
The project aims to analyze and predict certain aspects of books using various machine learning models. It involves:

Preprocessing data to correct issues such as bad column names and tabulations.

Performing feature engineering to transform data into a format that can be used for machine learning models.

Exploring different models, including linear regression, random forest, XGBoost, and neural networks, to predict outcomes based on the engineered features.

Utilizing advanced feature engineering techniques, such as term frequency and BERT model embeddings, to improve model performance.

Summary
The project starts with data loading and preprocessing, addressing any data quality issues.

Feature engineering is a critical step where the data is transformed, and irrelevant features are discarded. Special attention is given to handling outliers and engineering features that can significantly impact model performance.

Several models are trained and evaluated, including linear regression, random forest, XGBoost, and neural networks. The models are tested for overfitting and their performance is compared based on metrics such as mean squared error and r-squared values.

Advanced feature engineering techniques, specifically term frequency and BERT model embeddings, are explored to enhance model predictions. The impact of these techniques on different models is analyzed.

The project concludes that while linear regression did not benefit significantly from the advanced feature engineering, both random forest and XGBoost showed improved performance. The use of BERT model embeddings further influenced the model outcomes, with variations in performance metrics observed across different models.



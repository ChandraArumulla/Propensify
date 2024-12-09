# Propensify

 

**Introduction**

Propensify is a data-driven project aimed at developing a predictive model to identify potential customers for an insurance company. Utilizing historical data, the model forecasts the likelihood of prospects converting into customers, enabling targeted and efficient marketing strategies.


**Project Structure:**

- Train.xlsx: This Excel file contains the historical dataset provided by the insurance company. It includes features such as customer demographics, past 
   interactions, and whether or not each customer ultimately purchased insurance.
- Test.xlsx: Similar to train.xlsx, this Excel file contains data on potential customers to whom the model will be applied for prediction.
- Propensity_Model.ipynb: This Jupyter Notebook contains the Python code for data preprocessing, model building, hyperparameter tuning, model evaluation, and 
   result visualization.
- Source_code_pipeline.ipynb: Python script defining the data preprocessing pipeline used in the model training process.
- Propensify.joblib: Serialized joblib file containing the trained propensity model.
- Preprocessing_pipeline.joblib: Serialized joblib file containing the preprocessing pipeline used for data transformation.
- README.md: You are currently reading the README file providing an overview of the project.





**In this project:**

1. ***Setup***: Ensure you have a Jupyter environment set up (e.g., Jupyter Notebook or JupyterLab).
2. ***Data Preparation*:** 
   - Open Propensity_Model.ipynb.
   - Load Train.xlsx to explore the dataset.
   - Conduct data preprocessing, including missing value imputation, categorical variable encoding, and feature engineering.
3. ***Model Development*:**
   - Split the data into training and validation sets.
   - Train a machine learning model, such as a Random Forest Classifier.
   - Evaluate the model using metrics like accuracy, precision, recall, and ROC-AUC score.
   - Utilize GridSearchCV for hyperparameter tuning to optimize the model.
   - Experiment with an ensemble method, such as a Voting Classifier, to enhance predictive performance.
4. ***Deployment*:** Serialize the final model using joblib for easy loading and inference.




**Key Findings**

- Achieved an accuracy of ~86% on the test dataset, showcasing the model's capability in identifying potential customers effectively.
- Hyperparameter optimization further refined the Random Forest model's accuracy and generalization.
- Employing a Voting Classifier, combining Random Forest and SVM models, yielded superior prediction accuracy, underscoring the benefits of ensemble learning.
  




**Conclusion**

The Propensify project demonstrates a comprehensive approach to predicting customer behavior with significant accuracy. These insights can drive more effective marketing strategies and enhance customer engagement, contributing positively to business outcomes. Future work could explore additional model improvements and the integration of newer, more diverse data sources to refine predictions further.

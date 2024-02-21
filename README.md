
# Cardiovascular_risk Prediction
 - Supervised Learning 




## Authors

- [Jeetendra Sarpe](https://github.com/jtndr26)


### Context:
This research project focuses on developing a comprehensive cardiac disease prediction model using AI techniques. Utilizing a dataset containing diverse risk factors and clinical data, preprocessing methods are employed to extract crucial features. Machine learning models, including logistic regression and random forest, are trained on this data to enhance prediction accuracy. Additionally, comparisons with deep learning approaches are made to further improve prediction capabilities. The results highlight the potential of AI-based models in forecasting heart disease, providing valuable insights for early detection and proactive intervention strategies.

### Project Description:
Developed a robust classification model for predicting cardiac disease using machine learning techniques. Leveraged a diverse dataset encompassing statistical profiles, medical records, lifestyle factors, and medical test results to train the model. Employed preprocessing techniques to clean and extract important features for prediction. Evaluated the model's performance using rigorous cross-validation procedures, measuring accuracy, precision, recall, and F1-score. The model showcases the potential of AI-based approaches in effectively forecasting heart disease, offering valuable insights for early detection and proactive intervention in healthcare.


### Data Overview

- **id:** Unique identifier for each individual in the dataset.
- **age:** Age of the individual.
- **education:** Level of education attained by the individual.
- **sex:** Gender of the individual.
- **is_smoking:** Binary variable indicating if the individual is a smoker (1) or not (0).
- **cigsPerDay:** Average number of cigarettes smoked per day by the individual.
- **BPMeds:** Binary variable indicating if the individual is taking blood pressure medication (1) or not (0).
- **prevalentStroke:** Binary variable indicating if the individual has had a prevalent stroke (1) or not (0).
- **prevalentHyp:** Binary variable indicating if the individual has prevalent hypertension (1) or not (0).
- **diabetes:** Binary variable indicating if the individual has diabetes (1) or not (0).
- **totChol:** Total cholesterol level of the individual.
- **sysBP:** Systolic blood pressure of the individual.
- **diaBP:** Diastolic blood pressure of the individual.
- **BMI:** Body mass index (BMI) of the individual.
- **heartRate:** Resting heart rate of the individual.
- **glucose:** Blood glucose level of the individual.
- **TenYearCHD:** Binary variable indicating if the individual experienced a coronary heart disease event within the next ten years (1) or not (0).

## Approach

1. **Data Preparation:**
   - Perform data cleaning and preprocessing, handling missing values, and encoding categorical variables if necessary.
   - Split the dataset into training and testing sets to evaluate the model's performance.

2. **Feature Selection:**
   Conduct feature selection techniques such as correlation analysis or recursive feature elimination to identify the most relevant predictors for the classification task.

3. **Model Selection:**
   Choose appropriate classification algorithms for the task, such as K-Nearest Neighbors (KNN) and Random Forest, known for their effectiveness in handling classification tasks.

4. **Model Training:**
   - Train the KNN classifier on the training dataset, adjusting the number of neighbors (k) based on cross-validation performance.
   - Train the Random Forest classifier on the training dataset, adjusting parameters like the number of trees and maximum depth to optimize performance.

5. **Model Evaluation:**
   - Evaluate the performance of both models using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
   - Compare the performance of the KNN and Random Forest classifiers to identify the best-performing model for the given dataset.

6. **Hyperparameter Tuning:**
   Perform hyperparameter tuning for both models using techniques like grid search or random search to further optimize their performance.

7. **Model Validation:**
   Validate the final selected model(s) using the testing dataset to ensure its generalizability and robustness.

8. **Model Interpretation:**
   Interpret the results and gain insights into the factors contributing to the classification of individuals with or without coronary heart disease.

9. **Deployment and Monitoring:**
   Deploy the trained classification model into production, ensuring proper monitoring and maintenance for ongoing performance evaluation and updates.

### Result:
- After training and evaluating both the K-Nearest Neighbors (KNN) and Random Forest classifiers, the models achieved commendable performance in predicting coronary heart disease (CHD) based on the provided dataset.
- Both models exhibited high accuracy, precision, recall, and F1-score, indicating their effectiveness in correctly classifying individuals with or without CHD.

### Conclusion:
- The classification models, namely KNN and Random Forest, demonstrate promising capabilities in predicting the likelihood of individuals developing coronary heart disease.
- Leveraging advanced AI techniques, such as KNN and Random Forest, offers valuable insights into early detection and proactive intervention measures for CHD.
- Moving forward, the developed models can be deployed in clinical settings to assist healthcare practitioners in identifying high-risk individuals and implementing preventive measures, thereby contributing to improved patient outcomes and reducing the burden of cardiovascular diseases on public health systems.
 Student-Enrollment-Prediction

This project aims to predict student academic performance using machine learning techniques. The model utilizes a Random Forest Classifier trained on various student attributes to predict the likelihood of graduation success.

The model is trained on a dataset combining three sources: student_math_clean.csv, student_performance_data.csv and dataset (1).csv. These datasets contain information about student demographics, academic records, and enrollment details.

 Data Preprocessing;

1. Data Combination: The three datasets are concatenated to create a combined dataset.
2. Column Renaming: Column names are adjusted for consistency and clarity.
3. Feature Selection: Relevant features are chosen for model training, including age, study hours, attendance rate, academic performance in previous semesters and tuition fee status.
4. Data Splitting: The dataset is split into training and testing sets to evaluate the model's performance.

Model Training

A Random Forest Classifier is used for prediction. Hyperparameter tuning is performed using GridSearchCV to optimize the model's parameters for better accuracy. The model is then trained on the training data.

Evaluation

Model performance is evaluated using metrics such as classification report, confusion matrix and accuracy score. Additionally, cross-validation is performed to assess the model's generalization ability. Feature importances are also analyzed to understand the relative contribution of each feature to the prediction.

 Usage

1. Data Preparation: Ensure the required datasets are available and preprocessed as described.
2. Model Initialization: Initialize a Random Forest Classifier with the optimal hyperparameters found during grid search.
3. Model Training: Train the model on the preprocessed training data.
4. Prediction: Use the trained model to predict student performance on new data.

 Results

The model achieves an accuracy of 0.713 on the test dataset. Cross-validation results demonstrate the model's stability and ability to generalize to unseen data.

 Conclusion

This project demonstrates the potential of machine learning for predicting student academic performance. The Random Forest Classifier provides a robust and accurate model for this task. Future work could involve exploring other algorithms, incorporating additional features and refining the data preprocessing steps for improved performance.

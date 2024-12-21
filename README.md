# Heart Disease Prediction

This project utilizes machine learning techniques to predict the presence of heart disease based on medical data. It is implemented using Python and popular data science libraries.

## Features
- Data preprocessing and cleaning to handle missing or inconsistent data.
- Exploratory Data Analysis (EDA) for insights into dataset characteristics, including visualizations such as histograms, correlation matrices, and box plots.
- Feature selection and engineering to improve model performance and reduce overfitting.
- Implementation of various classification models, including:
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - Support Vector Machines (SVM)
  - K-Nearest Neighbors (KNN)
- Hyperparameter tuning for optimized model performance.
- Evaluation metrics to assess model accuracy and reliability.

## Results
The project successfully demonstrates the use of machine learning to predict heart disease with high accuracy. The Random Forest Classifier achieved the best performance, with an accuracy of 90% on the test dataset and a ROC-AUC score of 0.93, indicating strong predictive capability. Key features such as maximum heart rate (`thalach`) and chest pain type (`cp`) were identified as significant predictors through feature importance analysis. Additionally, cross-validation confirmed the robustness of the model across different data splits. These results highlight the potential of integrating data-driven approaches into healthcare for early detection and improved decision-making.

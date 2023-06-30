# Cardiovascular-Risk-Prediction-Classification-Project

This project focuses on analyzing a dataset from an ongoing cardiovascular study conducted in Framingham, Massachusetts. The goal of the project is to predict the 10-year risk of future coronary heart disease (CHD) for the residents of the town. The dataset consists of over 4,000 records and 15 attributes, including demographic, behavioral, and medical risk factors.

## Project Structure
The project is structured as follows:

Data Exploration and Preprocessing: In this section, the dataset is explored to understand its structure and characteristics. Missing values are handled, categorical columns are converted to numerical format, and statistical properties of the dataset are analyzed.

Data Visualization: Various data visualization techniques are employed to gain insights into the relationships between different attributes. Scatter plots, histograms, heatmaps, and pair plots are created to visualize correlations and patterns in the data.

Feature Manipulation: Feature manipulation techniques are applied to minimize feature correlation and create new features. Outliers are checked and addressed, and scaling is evaluated based on the nature of the dataset.

Feature Selection: Feature selection methods are utilized to identify the most relevant features for the prediction task. The importance of each feature is assessed to avoid overfitting and improve model performance.

Hypothesis Testing: Research hypotheses are formulated to investigate the relationships between specific attributes. Statistical tests such as the chi-square test, t-test, and correlation analysis are conducted to validate or reject the hypotheses.

Machine Learning Models: Three machine learning models are implemented for risk prediction: Logistic Regression, Decision Tree, and Support Vector Machine (SVM). The models are trained and evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1 score.

Hyperparameter Tuning: Cross-validation and hyperparameter tuning techniques are applied to optimize the performance of the models. GridSearchCV is used to search for the best combination of hyperparameters for Logistic Regression and Decision Tree models.

Model Explainability: Model explainability techniques such as permutation importance and SHAP values are employed to understand the contribution of each feature towards the model's predictions. This provides insights into the importance of different risk factors in predicting coronary heart disease.

Usage
To run the project, follow these steps:

Clone the project repository to your local machine.

Install the required dependencies by running pip install -r requirements.txt.

Run the Jupyter Notebook or Python script that corresponds to the specific task or analysis you are interested in. Make sure to update the file paths and configurations as needed.

Explore the results, visualizations, and evaluation metrics obtained from the different sections of the project.

Conclusion
This project provides valuable insights into the prediction of cardiovascular disease risk using a dataset from a cardiovascular study in Framingham, Massachusetts. By analyzing the dataset, performing data preprocessing, visualization, feature manipulation, and selection, as well as building and evaluating machine learning models, the project offers a comprehensive understanding of the risk factors associated with coronary heart disease. The findings can be used to inform healthcare professionals in assessing and managing the risk factors for cardiovascular diseases, thereby contributing to improved preventive strategies and interventions.

For more detailed information, refer to the project code, analysis, and documentation provided in this repository.

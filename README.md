# Stroke Prediction Model
This project aims to predict the occurrence of a stroke based on various health and demographic features. The dataset used for this project is sourced from Kaggle and contains information on factors such as age, gender, hypertension, heart disease, and more. The primary goal is to create a machine learning model to help identify individuals at risk of having a stroke.

## Models and Techniques
The project explores different machine learning models and techniques, including:

- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- Gradient Boosting Classifier

## Evaluation Metrics
The models are evaluated using metrics such as precision, recall, f1-score, and accuracy obtained from classification reports and confusion matrices.

## Key Findings
- The Gradient Boosting Classifier outperforms other models, achieving an accuracy of 0.92.
- The most important features in predicting stroke risk are 'age', followed by 'smoking_status' and 'work_type'.

## Visualizations
The project includes visualizations such as:
- Correlation heatmap to identify relationships between features
- Bar plots for feature importance in Random Forest and Gradient Boosting models
- Decision Tree visualization

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
To use this project, clone the repository and install the required dependencies. Run the Jupyter Notebook to train and evaluate the models on the stroke prediction dataset.

## Contributing
Contributions to improve the project are welcome. Please open an issue or submit a pull request with your changes.

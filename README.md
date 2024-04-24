# Disease prediction 

This project focuses on predicting if patient has a disease using machine learning techniques. The dataset comprises medical specifications of patients, including cholesterol levels, blood pressure, and types of chest pain, along with demographic information such as age and gender.

## Dataset
The dataset used for this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

## Model Building
### Random Forest
The initial model was constructed using a random forest classifier. Relevant features were selected based on their importance, and the model's accuracy was evaluated. The model yielded promising results, achieving an accuracy score of 0.688.

### Decision Tree Pruning
To further optimize the model, decision tree pruning was performed. GridSearchCV was utilized to fine-tune the decision tree using different hyperparameters. The optimal model was selected based on the criterion of entropy, resulting in improved performance.

## Evaluation
The performance of the models was evaluated using various metrics such as accuracy, precision, recall, and F1-score. Cross-validation was employed to ensure robustness and generalization of the models.

## Conclusion
Based on the evaluation results, the decision tree model using entropy criterion emerged as the most suitable for predicting disease occurance. Further enhancements and feature engineering could potentially improve the model's performance.

## Instructions for Use
1. Clone this repository.
2. Install the required dependencies and dataset.
3. Run the provided Python script to train and evaluate the models.

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn


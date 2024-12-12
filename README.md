README: Loan Default Prediction
Overview
This project uses machine learning algorithms to predict whether a loan will default. The models include Logistic Regression, Decision Trees, Random Forests, K-Nearest Neighbors, LightGBM, Neural Networks, and SVM. It includes data preprocessing, model training, evaluation, and prediction of test data.

Requirements -
Install the necessary libraries:

pip install pandas numpy scikit-learn lightgbm tensorflow matplotlib seaborn


Files - 
train.csv: The training dataset.
test.csv: The test dataset for predictions.
output_predictions/: Folder where prediction results are saved.


Steps -
 
Data Loading: Loads the training and test datasets.
Preprocessing: Encodes categorical variables and scales numerical features.
Model Training: Trains various models like Logistic Regression, Random Forest, and LightGBM.
Hyperparameter Tuning: Tunes models using GridSearchCV.
Prediction: Generates predictions and saves them to CSV files.
Model Evaluation: Prints classification reports for model performance.

Usage - 
Clone/download the repo.
Ensure the train.csv and test.csv files are in the same directory.

Run the script:

python loan_default_prediction.py
Check output_predictions/ for saved predictions.

Conclusion - 
This project demonstrates how to apply various machine learning models to predict loan defaults and evaluate their performance.

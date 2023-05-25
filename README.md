# Titanic Dataset Analysis - Kaggle

This repository contains Python code for analyzing and predicting survival on the Titanic using the Titanic dataset from Kaggle. The code utilizes a Random Forest Classifier model for prediction and includes data preprocessing steps such as imputing missing values, encoding categorical features, and standardization/normalization. 

## Requirements
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage
1. Download the Titanic dataset from Kaggle and save it in the appropriate directory.
2. Update the `train_data` and `test_data` variables in the code with the correct paths to the dataset files.
3. Run the code to perform the following steps:
   - Load and preprocess the Titanic dataset.
   - Impute missing data using mean values and fill missing categorical values.
   - Encode categorical features using OneHotEncoder.
   - Standardize and normalize the data.
   - Split the data into training and validation sets.
   - Train a Random Forest Classifier model on the training data.
   - Evaluate the model's performance on the validation data.
   - Generate predictions for the test data and save them in a CSV file.
4. Observe the evaluation metrics (accuracy, precision, recall, F1 score) and the confusion matrix to assess the performance of the model.
5. Use the generated submission file for submitting predictions to the Kaggle competition.

Feel free to modify the code according to your specific needs, such as adjusting the model hyperparameters, adding additional preprocessing steps, or experimenting with different classifiers.


## Acknowledgments
The code in this repository was created based on the Titanic dataset available on Kaggle. Special thanks to the original dataset contributors.


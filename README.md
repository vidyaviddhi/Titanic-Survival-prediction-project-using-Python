# Titanic Survival Prediction
This project uses a Random Forest Classifier to predict passenger survival on the Titanic, based on features such as age, passenger class, fare, and more. The model is optimized using Grid Search for hyperparameter tuning, and the dataset is preprocessed to handle missing values and scale features.

## Project Overview
Data Preprocessing: Cleaned, scaled, and encoded relevant features.  

Model Training: Utilized Random Forest with Grid Search for parameter tuning.  

Evaluation: Achieved an accuracy score of ~82% on test data.  

Prediction: Generated survival predictions for the Titanic test dataset.  


## Files
train.csv: Training dataset with labeled survival data.  

test.csv: Test dataset without survival labels.  

predictions.csv: Final output with survival predictions.  

## Dependencies
pandas  

scikit-learn  

numpy  

## Usage
Clone the repo and install dependencies.  

Run the script to generate predictions.  

Predictions are saved in predictions.csv.  

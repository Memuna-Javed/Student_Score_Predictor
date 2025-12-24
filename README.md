# Student Score Predictor via Linear Regression

This project implements a simple linear regression model to predict academic scores based on study hours. It covers the end-to-end machine learning pipeline from data ingestion to model evaluation.

## Dependencies
- Python 3.x
- Pandas
- Scikit-learn

## Project Structure
- Linear_Regression_Model.ipynb: Main notebook containing data preprocessing, training, and testing logic.
- Study hours and score DATA.csv: Dataset containing hours studied and corresponding scores.

## Implementation Details

### 1. Data Processing
The dataset is loaded via Pandas and split into features (x) and target (y). I utilized an 80/20 train-test split with a fixed random state to ensure reproducible results.

### 2. Model Training
The model is built using the Scikit-learn LinearRegression class. The training process involves fitting the model to the training set to determine the optimal coefficients.

### 3. Evaluation
Model performance is measured using the R-squared (R2) metric. 
Current model accuracy: 0.979 (97.9%)

### 4. Prediction
The script includes a section for testing the model on completely new data inputs. Results are organized into a final dataframe for side-by-side comparison of hours and predicted grades.


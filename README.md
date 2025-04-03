# Detection of bank debtors using supervised machine learning techniques

## Project Overview
This supervised learning project aims to classify bank customers based on their transaction history. The primary goal is to predict whether a customer will become a debtor using machine learning techniques.  

**Note:** The project has been developed mostly in Spanish.

## Dataset
The dataset consists of anonymized bank transactions and is provided in the following CSV files:

- train_features.csv - Contains 189 features per customer for model training.
- train_labels.csv - Contains labels indicating whether a customer became a debtor.
- test_features.csv - Contains transaction data for external evaluation.

The dataset (raw and processed) can be downloaded from [here](https://drive.google.com/drive/folders/1n9p-D30BjwD-MnJF2OsEux3APTORoHyK?usp=sharing).

## Project Structure
```
├── preprocess.ipynb         # Data preprocessing notebook
├── supervised.ipynb         # Supervised learning model training
├── best_model.ipynb         # Best model selection and test prediction
├── memoria.pdf              # Detailed report of methods and results
├── test_labels.csv          # Predicted labels for the test set
```

## Implementation Steps
### 1. Data Preprocessing
- Cleaning and transforming data
- Handling imbalanced data
- Feature selection using filter, wrapper, and embedded methods
- Splitting data into training and test sets

### 2. Supervised Learning Models
- Linear, Polynomial, and Logistic Regression
- Decision Trees
- Instance-Based Learning
- Support Vector Machines
- Neural Networks (Fully Connected with Dropout)

### 3. Evaluation
- Each model evaluated using F1-score as the primary metric.
- Hyperparameter tuning performed to optimize model performance.

## Contributors
- [Natalia Klinik](https://github.com/kliniik)
- [Elena Campanero Belda](https://github.com/elenacbelda)

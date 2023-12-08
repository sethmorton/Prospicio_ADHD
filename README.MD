# 🧠 ADHD Classification 🧑‍💻

This Python code analyzes data from multiple ADHD phenotypic studies to classify individuals as having ADHD or not using machine learning algorithms.

The main functions are: 

- `load_data()`: Loads data from multiple CSV files into DataFrames
- `preprocess_data()`: Merges, renames and selects columns from the DataFrames 📝   
- `clean_data()` Cleans the merged DataFrame by handling missing values 🧹
- `find_best_n_estimators_*()`: Finds optimal hyperparameters for KNN, Random Forest and Gradient Boosting classifiers 👩‍💻
- `train_predict_*()`: Trains and evaluates the classifiers on test data 🧪
- `plot_*()`: Various plotting functions like confusion matrices, correlations etc. 📈

The core steps are:

1. Load and preprocess data 📁
2. Clean the merged DataFrame  
3. Find optimal hyperparameters 🧑‍🔬
4. Train and evaluate classifiers 
5. Plot results 📊

The main() function ties it all together by: 

- Loading and preprocessing data
- Finding optimal hyperparameters
- Training/predicting with different classifiers   
- Plotting various analyses 📈

This provides a comprehensive framework to classify ADHD using multiple machine learning techniques and analyze the phenotype data. 🧠
```
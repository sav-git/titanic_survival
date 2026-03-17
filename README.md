# Titanic Survival Prediction: Machine Learning Project

![Titanic](https://images8.alphacoders.com/405/405029.jpg)

# Titanic Survival Prediction: Machine Learning Project

![Titanic](https://images8.alphacoders.com/405/405029.jpg)

An end-to-end machine learning classification project that predicts passenger survival using the historic Titanic dataset from Kaggle. This project demonstrates the full data science pipeline—from exploratory analysis to predictive modeling, including hyperparameter optimization.

## Project Overview
- **Objective:** Build and compare multiple classification models to predict survival outcomes.
- **Source:** Kaggle's "Titanic: Machine Learning from Disaster" competition dataset (train.csv, test.csv).
- **Approach:** Comprehensive workflow covering data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

## Technical Skills Demonstrated
### Data Processing & Analysis
- Data cleaning and imputation using **Pandas**.
- Exploratory Data Analysis (EDA) and visualization with **Matplotlib**, **Seaborn**, and **Missingno**.
- Feature engineering: creation of new features (FamilySize, AgeGroup) and encoding of categorical variables.
- Detection and analysis of outliers using statistical methods.

### Machine Learning & Modeling
- Implementation and comparison of multiple classification algorithms:
  - Logistic Regression
  - Support Vector Machines (linear and RBF kernels)
  - K‑Nearest Neighbors
  - Gaussian Naive Bayes
  - Decision Tree
- Model evaluation using accuracy, confusion matrix, and classification report.
- Hyperparameter tuning via **GridSearchCV** and **RandomizedSearchCV** with stratified k‑fold cross‑validation.
- Feature interaction analysis and statistical significance testing with logistic regression.

## Technologies Used
- **Python 3** (core programming language)
- **Pandas & NumPy** (data manipulation)
- **Matplotlib & Seaborn** (data visualization)
- **Missingno** (visualization of missing values)
- **Scikit-learn** (machine learning implementation)

## Key Project Components
1. **Data Preprocessing:** Handling missing values (Age, Embarked, Fare), encoding categorical variables (Sex, Embarked), feature scaling (StandardScaler), and outlier analysis.
2. **Exploratory Analysis:** Univariate and bivariate analysis, correlation matrices, and investigation of feature interactions (e.g., Pclass × Sex, AgeGroup × Sex).
3. **Model Development:** Building, training, and validating multiple classification models with default hyperparameters.
4. **Hyperparameter Optimization:** Systematic search for optimal parameters using cross‑validation.
5. **Performance Evaluation:** Comparing model accuracy before and after optimization, selecting the best model (Gaussian Naive Bayes) and generating predictions on the test set.

## Results
- The best‑performing model after optimization was **Gaussian Naive Bayes** with an accuracy of **77.2%** on the validation set.
- Hyperparameter tuning improved the Decision Tree model by almost 4 percentage points.
- Detailed results and comparisons are available in the notebook.

## Installation & Usage

1. Clone this repository or download the project files.
2. Install the required Python packages using the provided `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook `Titanic_Prediction.ipynb` to reproduce the analysis and predictions.
4. The final submission file (`titanic_prediction.csv`) will be generated in the working directory.

This project showcases practical implementation of foundational machine learning concepts and provides a complete workflow example suitable for production-level data science tasks.

PS: Please do not forget to drop a star if you like it!

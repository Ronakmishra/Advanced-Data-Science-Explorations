# Advanced Data Science Explorations

This repository contains the projects and analyses completed for exploring and applying data science techniques. Each project demonstrates the application of methods including data cleaning, feature selection, AutoML, interpretability, and neural network classification, as well as custom-built tools for data science mentorship.

---

## Table of Contents

- [Projects Overview](#projects-overview)
  - [Project 1: ML Data Cleaning and Feature Selection](#project-1-ml-data-cleaning-and-feature-selection)
  - [Project 2: AutoML](#project-2-automl)
  - [Project 3: Model Interpretability](#project-3-model-interpretability)
  - [Project 4: Comprehensive Report](#project-4-comprehensive-report)
  - [Project 5: Neural Network Classification](#project-5-neural-network-classification)
  - [Project 6: CustomGPT](#project-6-customgpt)
- [Datasets](#datasets)
- [How to Run](#how-to-run)
- [File Structure](#file-structure)
- [License](#license)

---

## Projects Overview

### Project 1: ML Data Cleaning and Feature Selection

- **Objective**: Explore and clean a dataset, perform feature selection, and evaluate its quality for predictive modeling.
- **Key Questions Addressed**:
  - Missing values and distributions.
  - Feature importance using multiple methods.
  - Effect of outliers and data imputation techniques.
  - Evaluation of variable independence and predictor ranges.
- **Notebook**: `Data_Science_Assignment1_Ronak.ipynb`

### Project 2: AutoML

- **Objective**: Use AutoML libraries (e.g., H2O.ai) to build predictive models and analyze their significance.
- **Key Questions Addressed**:
  - Evaluation of model relationships and assumptions.
  - Multicollinearity and variable significance in multivariate models.
  - Impact of regularization and hyperparameter tuning.
- **Notebook**: `AutoML_diabetesPrediction.ipynb`

### Project 3: Model Interpretability

- **Objective**: Interpret models using SHAP values and compare linear and tree-based models.
- **Tasks**:
  - Fit and interpret linear and tree-based models.
  - Use AutoML to find the best model.
  - Perform SHAP analysis to understand feature importance.
- **Notebook**: `Model_Interpretability_Ronak.ipynb`

### Project 4: Comprehensive Report

- **Objective**: Combine data cleaning, feature selection, modeling, and interpretability into a cohesive report.
- **Tasks**:
  - Address key questions about the data and models.
  - Provide insights through tables, graphs, and charts.
- **Notebook**: `FINAL_REPORT_Ronak.ipynb`

### Project 5: Neural Network Classification

- **Objective**: Build a neural network classifier for the TMNIST dataset.
- **Tasks**:
  - Create a tutorial for TMNIST classification.
  - Achieve high accuracy (>90%) with unique methodology and clear explanations.
- **Notebook**: `DS_TypeFace_TMNIST_002834798.ipynb`

### Project 6: CustomGPT

- **Objective**: Develop a CustomGPT for data science mentorship.
- **Description**: A chatbot designed to guide students in data science concepts and projects.

---

## Datasets

1. **IMDB Dataset** (`IMDB Dataset.csv`): Movie reviews for sentiment analysis.
2. **Diabetes Dataset** (`diabetes.csv`): Health data for predictive modeling.
3. **Netflix Titles Dataset** (`netflix_titles.csv`): Data on Netflix shows and movies for analysis.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required libraries (e.g., H2O.ai, SHAP, TensorFlow):
   ```bash
   pip install -r requirements.txt
   ```
3. Open the desired Jupyter Notebook in Google Colab or locally:
   ```bash
   jupyter notebook <notebook_name>.ipynb
   ```
4. Follow the instructions in each notebook to run the analysis.

---

## File Structure

```
Data_Science_Assignment-main/
├── AutoML_diabetesPrediction.ipynb       # AutoML project notebook
├── DS_TypeFace_TMNIST_002834798.ipynb    # Neural network classification notebook
├── Data_Science_Assignment1_Ronak.ipynb  # Data cleaning and feature selection notebook
├── FINAL_REPORT_Ronak.ipynb              # Comprehensive report combining all tasks
├── IMDB Dataset.csv                      # Dataset for analysis
├── Model_Interpretability_Ronak.ipynb    # Model interpretability notebook
├── NETFLIX_002834798.ipynb               # Netflix dataset analysis notebook
├── README.md                             # Repository documentation
├── diabetes.csv                          # Dataset for AutoML and prediction
├── netflix_titles.csv                    # Netflix dataset
```

## References

Help of various resources and references were taken. They are mentioned below:

1. https://github.com/aiskunks/YouTube/blob/main/A_Crash_Course_in_Statistical_Learning/ML_Data_Cleaning_and_Feature_Selection/ML_Data_Cleaning_and_Feature_Selection_Abalone.ipynb
2. https://www.kaggle.com/code/abhi011097/eda-feature-engineering-logistic-regression
3. https://www.kaggle.com/code/tirendazacademy/classification-analysis-with-xgboost
4. https://www.kaggle.com/code/aditimulye/adult-income-dataset-from-scratch
5. Sklearn documentation
6. Imblearn documentation
7. H2O.ai: https://docs.h2o.ai/
8. GitHub Notebook: https://github.com/aiskunks/YouTube/blob/main/9.%20A_Crash_Course_in_Statistical_Learning/AutoML/CC_Kaggle_AutoML_Regression_Melbourne_Housing.ipynb
9. GLM: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/data-science/glm.html
10. XGBoost: https://xgboost.readthedocs.io/en/stable/
11. Grid Search: https://docs.h2o.ai/h2o/latest-stable/h2o-docs/grid-search.html
12. GitHub Notebook: https://github.com/ajhalthor/model-interpretability/blob/main/Shap%20Values.ipynb
13. https://www.datacamp.com/tutorial/introduction-to-shap-values-machine-learning-interpretability
14. https://acerta.ai/blog/understanding-machine-learning-with-shap-analysis/
15. https://christophm.github.io/interpretable-ml-book/shap.html

---

## License

This repository is licensed under the [MIT License](LICENSE).


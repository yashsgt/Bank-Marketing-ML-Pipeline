# Bank Marketing: End-to-End Machine Learning Pipeline

### Building an Efficient Machine Learning Workflow with Python and Scikit-learn

## Project Overview

Machine Learning is not just about selecting an algorithm. Effective data preprocessing, feature transformation, and model integration play an equally important role in building a reliable workflow.

In this project, I developed an end-to-end Machine Learning Pipeline using the Bank Marketing dataset, Python, and Scikit-learn.

The project focuses on handling different types of features, automating preprocessing operations, integrating classification algorithms, and evaluating model performance through a structured pipeline.

## Objectives

- Build an end-to-end Machine Learning Pipeline.
- Handle missing values using SimpleImputer.
- Apply appropriate transformations to numerical and categorical features.
- Implement feature scaling and categorical encoding.
- Combine multiple preprocessing workflows using ColumnTransformer.
- Integrate preprocessing and classification using Pipeline.
- Train and evaluate different classification algorithms.
- Compare model performance using accuracy.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning and preprocessing |
| Jupyter Notebook | Interactive development environment |

## Machine Learning Pipeline

### 1. Feature Classification

Divided the dataset features into three categories:

- Numerical Features
- Ordinal Features
- Nominal Features

### 2. Numerical Transformation

Applied the following preprocessing techniques:

- SimpleImputer
- StandardScaler

### 3. Ordinal Transformation

Applied:

- SimpleImputer
- OrdinalEncoder
- StandardScaler

### 4. Nominal Transformation

Applied:

- SimpleImputer
- OneHotEncoder

### 5. ColumnTransformer

Used Scikit-learn's ColumnTransformer to combine all three preprocessing pipelines and apply transformations to the appropriate feature groups.

### 6. Machine Learning Pipeline

Integrated the preprocessing workflow with classification algorithms using Scikit-learn's Pipeline.

This made the complete workflow more structured and reusable.

## Model Training & Performance

Implemented and evaluated two classification algorithms:

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 90.16% |
| Random Forest Classifier | 90.41% |

Random Forest achieved a slightly higher accuracy than Logistic Regression in this experiment.

## Key Learning Outcomes

- Building end-to-end Machine Learning workflows.
- Understanding ColumnTransformer and Pipeline.
- Handling numerical and categorical features.
- Implementing missing-value imputation.
- Applying feature scaling and encoding.
- Training and comparing classification algorithms.
- Creating reusable preprocessing workflows.

## Future Scope

- Perform cross-validation for more reliable evaluation.
- Evaluate precision, recall, and F1-score.
- Perform hyperparameter tuning.
- Explore additional classification algorithms.
- Improve model performance through feature selection and optimization.

## Author

Yash Singh

Computer Science Engineering | Data Science
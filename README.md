# SparseSignals

SparseSignals explores scalable machine learning methods for sparse high-dimensional text data using R. The project uses the SMS Spam Collection dataset to compare regularization, dimension reduction, and kernel-based classification methods.

## Project Overview

The goal of this project is to study how modern statistical learning methods perform when classical models become less practical in high-dimensional settings.

The dataset contains SMS messages labeled as either spam or ham. After TF-IDF transformation, the text data becomes a sparse high-dimensional feature matrix, making it suitable for studying scalable learning methods.

## Methods

The project follows this workflow:

1. Text preprocessing and TF-IDF feature construction
2. Sparse matrix representation and data exploration
3. Penalized supervised learning
   - Logistic regression
   - Ridge regression
   - Lasso regression
4. Dimension reduction
   - Truncated SVD
   - Random projection
5. Kernel methods
   - Linear SVM
   - RBF kernel SVM
6. Model comparison and discussion

## Key Ideas

This project demonstrates several core ideas in high-dimensional statistical learning:

- Sparse feature representation
- Regularization
- Variable selection
- Dimension reduction
- Kernel-based nonlinear learning
- Accuracy, precision, recall, and F1-score evaluation

## Tools Used

- R
- R Markdown
- `tm`
- `glmnet`
- `caret`
- `irlba`
- `e1071`

## Dataset

The project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

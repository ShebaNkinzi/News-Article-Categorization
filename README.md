# News-Article-Categorization

A project for news article categorization using the [20 Newsgroups dataset](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html). This project demonstrates text preprocessing, feature engineering, model training (SVM & MLP), and evaluation in a real-world multi-class classification task.

Objective
To classify news articles into one of 20 categories using Support Vector Machine (SVM) and Multi-Layer Perceptron (MLP) models, with comprehensive data analysis and performance comparison.

Dataset Source: [scikit-learn.org - 20 Newsgroups](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html)

Files Included
The dataset file
Jupyter Notebook with full implementation 


Key Tasks Completed

Exploratory Data Analysis (EDA)
- Bar chart of article counts per category
- Word frequency histograms
- Boxplots of document lengths
- Scatter plot of PCA-reduced TF-IDF vectors

Feature Engineering & Reduction
- Compared unigrams vs bigrams/trigrams
- Used Chi-Square (χ²) for feature selection
- Applied PCA, t-SNE for dimensionality reduction

Preprocessing
- Removed headers, footers, and quotes
- Applied TF-IDF vectorization
- Handled stop words and high-dimensional text features

Model Training
- Trained SVM (Support Vector Machine)
- Trained MLP (Neural Network)
- Used stratified train-test split

Evaluation
- Accuracy, Macro-F1 Score
- Confusion matrices
- Cross-validation results
- Training time comparison

Reflection
- Discussed trade-offs between interpretability and high-dimensional features
- Analyzed overfitting risks in text classification



# Naive Bayes Text Classifier

This project implements a custom Naive Bayes text classifier from scratch to classify internet news articles into 20 categories. The implementation avoids external libraries for the model, focusing on understanding the fundamentals of Bayesian learning.

## Features
- Preprocesses and cleans a dataset of 20,000 news articles (from the Newsgroup dataset).
- Implements a Naive Bayes classifier using custom Python code.
- Evaluates performance using training and testing datasets.
- Reports accuracy and provides insights into classification results.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** NumPy, pandas, matplotlib (for results visualization)

## Dataset
The dataset consists of 20,000 newsgroup messages across 20 categories. For preprocessing:
- Removed metadata (e.g., `From`, `Subject`).
- Removed stop words and frequent terms to improve classification accuracy.

# Machine Learning with KNN, MLP and RandomForest for Fraud Detection

This project is a notebook about the [Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) and propose three classification models using, respectively, K-Nearest Neighbors, Multilayer perceptron and Random forest. As an unbalanced dataset, was proposed an undersampling solution to avoid overfitting and other side effects.  All models used grid search to estimate hyperparameters, and the results (accuracy, precision, recall) are described at the end of this script.

# Get started

## Requirements

 - [Anaconda](https://docs.anaconda.com/anaconda/install/)
 - [Jupyter Notebook](https://jupyter.org/install)

## Install environment

- Extract the creditcard.csv.zip at input/creditcardfraud
- Install all requirements and active the conda environment.

```shellscript
conda env create -f environment.yml
conda activate am-t1-credit-card-fraud-detection
```

## Running

`jupyter notebook main.ipynb`



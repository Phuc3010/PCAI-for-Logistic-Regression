# Principal Components Analysis based Imputation for LogisticRegression
This repository contains all codes of our paper "Principal Components Analysis based Imputation for LogisticRegression."

Implementation descriptions
data_loader.py: Loading dataset include: Parkinson, Gene, MNIST and Fashion MNIST dataset
model.py: Imputation model including: GAIN, MissForest, MICE, KNNImputer, etc.
main.py: Running imputation process and Logistic Classifier. Metrics to compare different methods are RMSE, Running time and Accuracy.

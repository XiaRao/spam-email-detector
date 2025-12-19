# spam-email-detector
Spam email classification on a word-count dataset: compare Naive Bayes, Logistic Regression, and Linear SVM with ROC-AUC and interpret key predictive words.

This project investigates spam email classification using dataset from Kaggle of 5,172 emails represented by 3,000 word-count features (bag-of-words). I investigated 3 classic models (Naive Bayes, Logistic Regression, and Linear SVM) under consistent train/test splits and evaluation metrics (ROC-AUC). Model interpretability is analysed by identifying the most influential words for predicting spam and discuss why certain models perform better on count-based text features.

The repository is fully reproducible with documented dependencies and clear run instructions.

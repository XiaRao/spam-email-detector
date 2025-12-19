# spam-email-detector
Spam email classification on a word-count dataset: compare Naive Bayes, Logistic Regression, and Linear SVM with ROC-AUC and interpret key predictive words.

This project investigates spam email classification using dataset from Kaggle of 5,172 emails represented by 3,000 word-count features (bag-of-words). I investigated 3 classic models (Naive Bayes, Logistic Regression, and Linear SVM) under consistent train/test splits and evaluation metrics (ROC-AUC). Model interpretability is analysed by identifying the most influential words for predicting spam and discuss why certain models perform better on count-based text features.

Research Question: Among Naive Bayes, Logistic Regression, and Linear SVM, which model achieves the best spam classification performance on this word-count dataset, and why?

Methods: Naive Bayes, Logistic Regression, Linear SVM.

Key Results:
<img width="580" height="435" alt="output" src="https://github.com/user-attachments/assets/b2c2bdf7-925d-4999-b0cc-c485a5e296d8" />
<img width="571" height="455" alt="output2" src="https://github.com/user-attachments/assets/1bf8e152-7517-46d6-bc49-466bb4ff0e2f" />
<img width="558" height="455" alt="output3" src="https://github.com/user-attachments/assets/587cce4a-e3b4-4c46-bee3-838d15311aa0" />
<img width="630" height="470" alt="output4" src="https://github.com/user-attachments/assets/ebb9f620-70d4-4037-88dc-c772e446fdf7" />
<img width="1356" height="390" alt="output5" src="https://github.com/user-attachments/assets/94eff104-65f7-4766-bf96-ce23a2c9d478" />
<img width="629" height="470" alt="output6" src="https://github.com/user-attachments/assets/9c47c1d3-0544-4a11-a210-e5b706fbe1f9" />


The repository is fully reproducible with documented dependencies and clear run instructions.

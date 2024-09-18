# Imbalanced-classification-credit-card-fraud-detection

#### Overview:
This project focuses on developing a machine learning model to detect credit card fraud using imbalanced classification techniques. Credit card fraud detection is a critical task in the financial industry, where timely identification of fraudulent transactions can minimize losses.

### Problem Statement
Credit card fraud detection is an imbalanced classification problem, where the minority class (fraudulent transactions) is significantly outnumbered by the majority class (legitimate transactions). This imbalance affects model performance and requires specialized techniques.

### Conclusions
At the end of the training, out of 56,961 validation transactions, we are:

* Correctly identifying 66 of them as fraudulent.  
* Missing 9 fraudulent transactions.  
* At the cost of incorrectly flagging 441 legitimate transactions.  

In the real world, one would put an even higher weight on class 1, so as to reflect that False Negatives are more costly than False Positives.

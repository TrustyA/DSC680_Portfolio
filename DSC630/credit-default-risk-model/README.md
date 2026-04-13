Overview

This project focuses on predicting whether a customer will default on their next credit card payment. The goal was to take a real-world financial dataset and build a model that could identify risk patterns, while also understanding the limitations that come with imbalanced data.

Objective

The objective of this project was to develop a classification model that could accurately predict default risk. A key part of this was evaluating how well the model performs on both majority and minority classes, since default cases are less common but more important to detect.

Data

The dataset used for this project contains financial and demographic information for approximately 30,000 customers. It includes features such as credit limit, payment history, bill statements, and demographic variables. The target variable indicates whether a customer defaulted on their next payment.

Tools & Technologies

Python, Jupyter Notebook, pandas, NumPy, scikit-learn, matplotlib, seaborn

Methodology

The data was first cleaned and prepared by handling missing values and separating features from the target variable. A train/test split was applied to evaluate model performance.

A baseline logistic regression model was created first to establish a reference point. After evaluating the results, it became clear that class imbalance was affecting performance, especially for predicting defaults. To address this, a balanced logistic regression model was implemented using class weighting.

Model performance was evaluated using accuracy, precision, recall, and ROC-AUC to get a more complete understanding of how well the model handled both classes.

Results

The baseline model achieved moderate overall accuracy, but performed poorly when identifying default cases. After applying class balancing, there was a slight improvement in ROC-AUC and better detection of the minority class, though tradeoffs in accuracy were observed.

This highlighted how misleading accuracy alone can be when working with imbalanced datasets.

Key Takeaways

This project shows the importance of model evaluation beyond accuracy, especially in financial risk scenarios. It also demonstrates experience with classification models, handling imbalanced data, and interpreting performance metrics in a meaningful way.

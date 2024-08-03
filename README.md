# Predicting Customer Default Payments with Key Features Using Data Mining Techniques


#### Abstract
The study addresses the challenge of predicting credit card defaults using a dataset of Taiwanese credit card users. It employs Recursive Feature Elimination with Cross-Validation (RFECV) to identify key predictors and assesses seven machine learning models. The research highlights the significant accuracy improvements achieved through feature selection, with Random Forest models showing the most notable enhancement. This provides valuable insights for financial institutions to enhance risk management protocols.

#### Keywords
Machine Learning, Recursive Feature Elimination, Cross-Validation, Random Forest, Data Quality

#### Introduction
Credit card defaults pose substantial risks to lenders and financial stability. Accurate prediction models are crucial for mitigating these risks. This study leverages data mining techniques on a Taiwanese dataset to develop predictive models for credit card defaults. Effective prediction can aid financial institutions in proactive risk management and help borrowers make informed financial decisions.

#### Background
Previous research has applied various data mining techniques to similar datasets, showing the effectiveness of models like ANNs, Random Forest, and LightGBM. This study builds on these findings, emphasizing the importance of feature selection in improving prediction accuracy.

#### Methodology
The dataset contains 30,000 instances and 24 features. Data preprocessing involved one-hot encoding categorical variables, dropping unnecessary rows and columns, splitting the dataset into training and testing sets, and normalizing the data. Seven machine learning models were employed: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbour (KNN), Support Vector Machine (SVM), Gaussian Naïve Bayes, and Bernoulli Naïve Bayes. RFECV identified the most significant features, which were then used to train and evaluate the models.

#### Results
Feature selection significantly improved model accuracy. The Random Forest model showed the highest accuracy improvement, from 80.69% to 82.08%. KNN and Logistic Regression also saw notable accuracy enhancements. Some models, like Gaussian Naïve Bayes, experienced slight decreases in accuracy, highlighting areas for further investigation.

<img width="499" alt="Screen Shot 2024-07-17 at 3 27 15 PM" src="https://github.com/user-attachments/assets/a28f583a-129d-4cfc-8336-3add0fc4b9be">

Table: Compare Model Accuracy Between All and Significant Features

#### Discussion
The study demonstrates the benefits of feature selection across various machine learning algorithms, with significant accuracy improvements noted in several models. However, data quality issues, such as negative values and filled missing values, present limitations. Addressing these issues is crucial for improving model performance.

#### Conclusion
The study successfully enhances credit card default prediction models using advanced data mining techniques and RFECV for feature selection. These findings contribute to improved risk management strategies in the financial sector. Future research should explore advanced machine learning algorithms like Heterogeneous Ensemble methods to further enhance prediction accuracy and robustness.

#### Future Work
Exploring Heterogeneous Ensemble methods can integrate strengths from various machine learning algorithms, potentially leading to more robust and accurate predictions, thereby enhancing credit risk management practices.

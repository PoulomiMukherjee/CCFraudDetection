# Credit Card Fraud Detection

#### Problem Statement:

For many banks, retaining high profitable customers is the number one business goal. Banking fraud, however, poses a significant threat to this goal for different banks. In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

It has been estimated by Nilson report that by 2020 the banking frauds would account to $30 billion worldwide. With the rise in digital payment channels, the number of fraudulent transactions is also increasing with new and different ways.

In the banking industry, credit card fraud detection using machine learning is not just a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees, and denials of legitimate transactions. The objective of this project is to predict fraudulent credit card transactions with the help of machine learning models.

#### Data Preview:

The data set includes credit card transactions made by European cardholders over a period of two days in September 2013. Out of a total of 2,84,807 transactions, 492 were fraudulent.

This data set is highly unbalanced, with the positive class (frauds) accounting for 0.172% of the total transactions.

The data set has also been modified with Principal Component Analysis (PCA) to maintain confidentiality.

Apart from ‘time’ and ‘amount’, all the other features (V1, V2, V3, up to V28) are the principal components obtained using PCA. The feature 'time' contains the seconds elapsed between the first transaction in the data set and the subsequent transactions. The feature 'amount' is the transaction amount.

The feature 'class' represents class labelling, and it takes the value 1 in cases of fraud and 0 in others.

#### Project Pipeline:

The steps followed in this case study are:

1. Loading and understanding the data
2. Data visualization and EDA
3. Preparing the data for modeling

After this step, project is divided into 2 parts, one is without implementing techniques to balance the classes in the dataset and the other is applying models to the balanced dataset using three different techniques to balance, and finding out the best accurate model for the same.

4. Modeling with imbalanced dataset
5. Modeling with balanced dataset
6. Recommendations

For Modeling, three Classification Models were used:

- Logistic Regression
- Random Forest
- XGBoost

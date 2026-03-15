# Credit Card Customer Segmentation & Churn Risk Prediction (Group 17)

## Project Overview
This project focuses on identifying distinct customer segments within a credit card dataset of approximately 8,950 active cardholders. By applying unsupervised learning techniques, we aim to:
- **Segment Customers**: Use K-Means clustering to identify behavioral groups based on spending and payment habits.
- **Predict Churn Risk**: Analyze cluster characteristics to identify customers at risk of churn or those who may require specific financial interventions.



## Dataset Details
The analysis uses the [CC GENERAL.csv](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata) dataset, which tracks 18 behavioral variables for customers over a 6-month period. Key features include:
* **BALANCE**: Balance amount left in their account to make purchases.
* **PURCHASES**: Amount of purchases made from account.
* **CASH_ADVANCE**: Cash in advance given by the user.
* **PURCHASES_FREQUENCY**: How frequently the Purchases are being made (score between 0 and 1).
* **CREDIT_LIMIT**: Limit of Credit Card for user.

## Methodology
1. **Data Preprocessing**: Handling missing values (Minimum Payments and Credit Limit) and feature scaling using `StandardScaler`.
2. **Exploratory Data Analysis (EDA)**: Visualizing distributions and correlations using Seaborn and Matplotlib.
3. **Dimensionality Reduction**: Implementing PCA (Principal Component Analysis) to visualize high-dimensional clusters.
4. **Clustering**: Applying the Elbow Method and Silhouette Score to determine the optimal number of clusters for K-Means.



## Group Members Information
| | NAME | EMAIL | GITHUB REPOSITORY |
| :--- | :--- | :--- | :--- |
| 1 | Ilevbare Benjamin Joseph | benjoevybenjamin@gmail.com | https://github.com/Benjoevy |
| 2 | Olorunnishola Taiwo | olorunnisholato7@gmail.com | https://github.com/Te-ne |
| 3 | Bertrand Rosesharon Oluoma | bertsharon14@gmail.com | https://github.com/Ro-nnie12 |
| 4 | Dan Godwin Uduak | nagodwindan@gmail.com | https://github.com/nagodwindan-sys/Godwin |
| 5 | Okanga Chukwuma Jeffrey | jeffokanga@gmail.com | https://github.com/jeph29 |
| 6 | Timothy Orungbemi Anuoluwapo | orungbemitimothy@gmail.com | https://github.com/Timothy-info |
| 7 | Faith Festus Esenam | faithita15@gmail.com | https://github.com/Faithy-15 |
| 8 | Adedokun Joshua Adedamola | Adedokunjoshua35@gmail.com | https://github.com/ADEDAMOLA-20 |
| 9 | Okorigwe Udonna Michael | anthonyokorigwe@gmail.com | https://github.com/Okorigwe123 |
| 10 | Oluwaseun Shoniran | seun.shoniran16@gmail.com | https://github.com/NirvanaShelly |

## Requirements
To run the notebook, you will need:
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
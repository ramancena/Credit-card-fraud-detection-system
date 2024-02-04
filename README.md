# Credit Card Fraud Detection

In 2020, consumers reported losing a staggering $3.3 billion to fraud, with a notable $1.5 billion increase from the previous year. Businesses globally are projected to suffer $75 billion in e-commerce fraud losses between 2019 and 2023, with the U.S. alone accounting for 33.57% of gross card fraud losses worldwide in 2019.

Credit card fraud, the second most reported identity theft type in 2020, saw over 390,000 reported cases, resulting in a loss of $149 million in the United States alone. New account credit card fraud attempts spiked by 48% in 2020 compared to the previous year.

To combat these rising threats, an effective fraud detection system is crucial, capable of identifying and preventing fraudulent activities accurately and in real-time.

**Dataset Overview:**
The dataset comprises 1.8 million transactions involving 1000 credit cards and 800 merchants. It includes various transaction statistics, regional spending habits, merchant category usage, and time-based usage patterns.

**Approach:**
The foundation of credit card fraud detection relies on analyzing cardholder spending behavior. Historical trends were studied by calculating daily, weekly, and monthly rolling averages of customer spending and transaction counts.

**Implementation:**
After data cleaning and feature engineering, classification algorithms, including Logistic Regression, Random Forest, and Gradient Boosted Trees, were applied. Hyperparameter tuning was performed using 3-fold cross-validation.

**Model Evaluation:**
Given the highly imbalanced dataset, the area under the Precision-Recall curve was chosen as the model evaluation parameter. The optimal probability threshold was determined by maximizing the F1 score.

**Technology Used:**
The entire project was implemented using PySpark and SparkSQL, ensuring scalability and efficiency in handling large datasets.

By leveraging advanced analytics and machine learning, this Credit Card Fraud Detection system aims to proactively identify and prevent fraudulent activities, safeguarding both consumers and businesses from financial losses.

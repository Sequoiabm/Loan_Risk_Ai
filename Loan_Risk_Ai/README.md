# Loan_Risk_Ai

---

**Credit Risk Analysis Report:**


* **Purpose** : The analysis is focused on evaluating the performance of logistic regression models for classifying loans into 'healthy' and 'high-risk' categories using financial data.
* **Data and Prediction Goal** : The data includes various financial indicators, with the goal to predict loan status (healthy or high-risk).
* **Variables to Predict** : The loan_status variable is key, categorized into '0' (healthy loan) and '1' (high-risk loan).
* **Machine Learning Process** :
* **Step 1** : Data is split into training and testing sets.
* **Step 2** : A logistic regression model is created using the original data.
* **Step 3** : Model evaluation includes accuracy score, confusion matrix, and classification report.
* **Methods Used** : Logistic Regression, with mention of using RandomOverSampler for data resampling.

---

**Results**

* **Machine Learning Model 1 (Original Data)** :
* **Accuracy** : 0.99
* **Precision and Recall for '0' (healthy loan)** : Precision - 1.00, Recall - 0.99
* **Precision and Recall for '1' (high-risk loan)** : Precision - 0.85, Recall - 0.91
* **Machine Learning Model 2 (Resampled Data)** :
* **Accuracy** : Not explicitly stated in the snippet
* **Precision and Recall for '0' (healthy loan)** : Presumably the same as Model 1
* **Precision and Recall for '1' (high-risk loan)** : Slight drop in precision (0.84) but a significant increase in recall (0.99)

---

**Summary**

* **Comparison** : The first model is balanced, while the second model (with oversampling) shows an improvement in recall for high-risk loans at a slight cost to precision.
* **Recommendation** : Depends on the priority - if catching as many high-risk loans as possible is crucial, Model 2 seems better due to its higher recall. However, for balanced performance, Model 1 might be preferable.

---

---

**Sources and Documentation:**

- [https://imbalanced-learn.org/stable/]()
- [https://docs.python.org/3/library/pathlib.html]()
- [https://scikit-learn.org/stable/]()

---

Machine learning Maths resources:

- [https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/introduction-to-trend-lines/a/linear-regression-review#:~:text=Linear%20regression%20is%20a%20process,is%20useful%20when%20making%20predictions.]()
- [https://www.khanacademy.org/math/statistics-probability/advanced-regression-inference-transforming]()

For additional notes on the above documentation you can refer to my notes below:

---

**Link To my Personal Notes (notion):**

- [https://jolly-hen-e31.notion.site/Supervised-Learning-a84845822ec64b2a8137534b5cba0776
  ]()

---

---

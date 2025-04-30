This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, and the goal is to identify frauds with high precision and recall.
---

**1. Loading Libraries and Dataset**

- Imports required libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.
- Loads the credit card fraud dataset.
- Checks the shape of the dataset, missing values, and data types.

---

**2. Exploratory Data Analysis (EDA)**

- Analyzes the distribution of the 'Class' feature to observe class imbalance.
- Plots histograms of features such as 'Time', 'Amount', and the PCA-transformed features (V1–V28).
- Uses a correlation matrix and heatmap to understand feature relationships.

---

**3. Data Preprocessing**

- Scales the 'Amount' and 'Time' features using StandardScaler.
- Removes the original 'Amount' and 'Time' columns and adds their scaled versions.
- Separates the dataset into features (X) and labels (y).

---

**4. Train-Test Split**

- Splits the data into training and testing sets using an 80/20 ratio.

---

**5. Model Training and Evaluation**

- Trains and evaluates several machine learning models, including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost (if available)
- Evaluates models using accuracy, confusion matrix, precision, recall, F1-score, and ROC-AUC.

---

**6. Performance Comparison**

- Compares the evaluation metrics of all models in a tabular format.
- Plots ROC curves to compare model performance visually.

---

**7. Conclusion**

- Identifies the best-performing models (likely Random Forest and XGBoost).
- Highlights the importance of recall and precision due to the imbalanced nature of the dataset.

---

# EMPLOYEE PERFORMANCE ANALYSIS 

![image](https://github.com/user-attachments/assets/c7056587-b207-4f85-84b1-9bc6ae8bd168)

## **Project Summary:**
### Goal: Predict employee performance rating based on dataset features.
- **Dataset**: INX Future Inc (IABAC). 1200 rows, 28 features.
- **Key Insights**: Department-wise performance, top factors affecting employee performance, trained model for prediction, and recommendations to improve performance.

---

**1. Requirements:**
- Data provided by IABAC™ based on INX Future Inc. The project was conducted in Jupyter using Python.

**2. Analysis:**
- **Features:** Numerical, categorical, and ordinal.
- **Important Features:** EmpNumber (not relevant), Gender, Education, MaritalStatus, JobRole, etc.

**3. Data Analysis:**
- **Univariate Analysis:** Distribution of categories and numerical data.
- **Bivariate Analysis:** Relationship with performance rating.
- **Multivariate Analysis:** Relationships across features.

**4. Exploratory Data Analysis:**
- Distribution and statistical checks for features.
- Skewness and Kurtosis analysis for normality.
- Visualizations for feature relationships.

**5. Data Preprocessing:**
- Missing value check, encoding categorical data, handling outliers, feature transformation, scaling.

**6. Feature Selection:**
- Dropped unique columns and performed PCA to reduce features from 28 to 25.

**7. Machine Learning Model:**
- Algorithms used: SVM, Random Forest, and Artificial Neural Networks (ANN).
- Best Model: ANN with 95.80% accuracy.

**8. Model Saving:**
- Saved the trained model using Pickle for future predictions.

---

**Goal 1: Department-wise Performances:**
- Violinplot and Countplot used for performance distribution across departments.
- Findings: Sales and Development departments have the highest performers. Female employees in HR perform well.

**Goal 2: Top 3 Factors Affecting Performance:**
- Important factors: Environment satisfaction, salary hike percentage, and experience in current role.

**Goal 3: Trained Model for Prediction:**
- Trained models: SVC (98.28%), Random Forest (95.61%), ANN (95.80%).

**Goal 4: Recommendations to Improve Performance:**
- Focus on environment satisfaction, salary hikes, and work-life balance.
- Promote employees regularly, focus on female candidates in HR, and improve job satisfaction and relationships.


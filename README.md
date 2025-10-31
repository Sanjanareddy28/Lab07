# HR Logistic Regression – Employee Retention Prediction

### 📘 Objective
To predict whether an employee will leave or stay in a company based on HR attributes using Logistic Regression.

---

### 📊 Dataset
- **Dataset Name:** HR Analytics Dataset  
- **Source:** [Kaggle – HR Analytics](https://www.kaggle.com/giripujar/hr-analytics)  
- **File Used:** `HR_comma_sep.csv`  
- Contains attributes such as satisfaction level, last evaluation, project count, average monthly hours, time spent at company, promotions, salary level, and employee retention (`left` column).

---

### 🧠 Steps Involved
1. **Data Loading & Cleaning**  
   - Loaded dataset and checked for missing or inconsistent data.  
   - Standardized column names and selected relevant features.

2. **Exploratory Data Analysis (EDA)**  
   - Generated a correlation heatmap to identify variables impacting retention.  
   - Analyzed relationships between numerical and categorical features.

3. **Visualization**  
   - Bar charts: **Salary vs Retention** and **Department vs Retention**.  
   - Correlation Heatmap for numeric attributes.

4. **Feature Engineering**  
   - Encoded the `salary` categorical column into numeric dummy variables.  
   - Selected key predictors for model training.

5. **Model Building**  
   - Applied Logistic Regression using `sklearn.linear_model.LogisticRegression`.  
   - Split dataset into 80% training and 20% testing data.

6. **Model Evaluation**  
   - Accuracy: ~83%  
   - Evaluated using Confusion Matrix and Classification Report.

7. **Prediction**  
   - Predicted whether a new employee (based on given features) would stay or leave.

---

### 🧮 Tools & Libraries Used
- **Python**  
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Model training and evaluation  
- **Google Colab** – Development environment  

---

### 📈 Results
- The Logistic Regression model successfully predicts employee retention with ~83% accuracy.  
- **Key Influencing Factors:**  
  - Satisfaction level  
  - Working hours  
  - Promotion history  
  - Salary level  

---

### 🔗 Notebook Link
[View HR Logistic Regression Notebook](HR_Logistic_Regression.ipynb)

---

### 🧑‍💻 Author
**Sanjana Reddy**  
*Department of Computer Science & Engineering*

## 🔍 Project Overview
This project focuses on predicting whether a student will pass or fail based on two critical academic factors: **study hours** per week and **class attendance** percentage. Using a **Logistic Regression** model, the goal is to classify students as either passing (1) or failing (0) based on these inputs.

---

## 🎯 Objectives
- Build a simple and interpretable classification model using logistic regression.
- Understand how study behavior and attendance affect academic performance.
- Evaluate the model's accuracy and visualize its performance using a confusion matrix.

---

## 📊 Dataset
A synthetic dataset was created with the following columns:
- `Study Hours`: Number of hours a student studies per week.
- `Attendance`: Percentage of classes attended.
- `Pass`: Binary target (1 for pass, 0 for fail).

The dataset includes 10 student records where a clear distinction exists between those who pass and those who fail.

---

## 🛠️ Tools and Libraries
- **Python 3**
- **Pandas** and **NumPy** – for data manipulation
- **Matplotlib** and **Seaborn** – for visualization
- **Scikit-learn** – for model building and evaluation

---

## ✅ Process
1. **Data Creation & Exploration**  
   Created a custom dataset and performed basic statistical exploration.

2. **Data Visualization**  
   Used scatter plots to understand the relationship between study hours, attendance, and outcomes.

3. **Model Training**  
   Trained a logistic regression model using `Study Hours` and `Attendance` as features.

4. **Model Evaluation**  
   Evaluated model using accuracy score and confusion matrix. Achieved perfect classification due to the clear data separation.

---

## 📌 Insights & Future Work
- Students with higher study hours and better attendance are more likely to pass.
- Real-world data with more records and noise would test the model’s generalization.
- Future enhancements could include adding more features like assignment completion or prior grades.
- Try other models like Decision Trees, SVMs, or Random Forests for comparison.

---

## 📁 Files
- `Student.ipynb`: Jupyter Notebook with the full code and analysis.
- `README.md`: Project overview and documentation.

---

## ✨ Author
Harshita Kaushal  

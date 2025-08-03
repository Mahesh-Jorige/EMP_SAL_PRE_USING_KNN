# EMPLOYEE_SALARY_PREDICTION_USING_KNN
# EMPLOYEE_SALARY_PREDICTION_USING_KNN

This project helps **predict the salary category of an employee** (High or Low) using the **K-Nearest Neighbors (KNN)** algorithm based on data like their age, education, experience, etc.

---

## 🔰 What is This?

- A **machine learning web app** built using **Python** and **Streamlit**.
- It uses a **CSV file** containing employee data.
- Based on that data, it predicts whether the employee's salary is **>50K or <=50K**.

---

## 🧑‍💻 Technologies Used

| Tool/Library   | Purpose                            |
|----------------|------------------------------------|
| Python         | Main programming language          |
| pandas         | To read and process the CSV file   |
| scikit-learn   | For KNN algorithm and model building |
| Streamlit      | To create a web-based app          |
| joblib         | To save/load the trained model     |

---

## 📁 Project Structure
EMP_SAL_PRE_USING_KNN/
│
├── emp_using_knn/
│ ├── knn_model.py # Python file to train and save the model
│ ├── app.py # Streamlit web app to predict salary
│ └── adult.csv # Dataset with employee info
│
├── README.md # You're reading it now

---

## 🚀 How to Run the Project

Follow these steps:

1. ✅ **Clone this repository:**

```bash
git clone https://github.com/Mahesh-Jorige/EMP_SAL_PRE_USING_KNN.git
cd EMP_SAL_PRE_USING_KNN/emp_using_knn

✅ Install the required libraries:

bash
Copy code
pip install pandas scikit-learn streamlit joblib
✅ Train the model:

bash
Copy code
python knn_model.py
This will create a file named knn_model.pkl.

✅ Run the web app:

bash
Copy code
streamlit run app.py
🌐 Now open your browser. The app will open there.

📊 Sample Output
You select inputs like Age, Education, Hours per week etc.

The app will tell whether the salary is >50K or <=50K

🤔 What is KNN?
K-Nearest Neighbors is a simple ML algorithm that:

Looks at the 'K' most similar records

Predicts the result based on those

Example:
If 3 similar people earn >50K, you probably do too.

##📌 Who Can Use This?
Students learning ML

Beginners in Python

Anyone curious about data-based prediction


# 🧠 Employee Salary Prediction

This project builds a machine learning model to predict employee salaries based on various features like education, experience, job role, and location. It uses data preprocessing, encoding techniques, and regression models to generate accurate salary predictions.

---

## 📌 Problem Statement

In modern organizations, accurate salary forecasting is essential for budgeting and HR planning. Manual estimation often leads to bias and inconsistency. This project aims to create a data-driven approach using machine learning to predict employee salaries with high accuracy based on their experience, education level, job role, location, and other relevant attributes.

---

## 📊 Dataset

**Source**: Kaggle  
**Name**: [Salary Prediction Data by mrsimple07](https://www.kaggle.com/datasets/mrsimple07/salary-prediction-data)  
**Features Used**:
- `Experience`
- `Age`
- `Education`
- `Location`
- `Job_Title`
- `Gender`
- `Salary` (target)

---

## 🔧 Tech Stack / Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (Pipeline, ColumnTransformer, LinearRegression)
- Jupyter Notebook

---

## ⚙️ Workflow

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Preprocess data (handle categorical features with `OneHotEncoder`)
4. Split into training and testing sets
5. Build a machine learning pipeline
6. Train the model
7. Evaluate using R² Score and MSE
8. Predict salary for new employee inputs

---

## 📸 Screenshots

### 🔹 Dataset Preview
<img width="680" height="255" alt="Screenshot 2025-07-22 134349" src="https://github.com/user-attachments/assets/dd8b17db-c9ef-48bd-b678-32d847467cea" />


### 🔹 Salary Distribution
<img width="1117" height="585" alt="Screenshot 2025-07-22 134534" src="https://github.com/user-attachments/assets/a99ebecb-a3f6-43d9-81fc-b5650e8c45cb" />


### 🔹 Model Accuracy
<img width="676" height="543" alt="image" src="https://github.com/user-attachments/assets/f9632479-6263-49a2-b6b5-2dc41992232b" />


### 🔹 Sample Prediction
<img width="1142" height="161" alt="image" src="https://github.com/user-attachments/assets/4b6e16fd-de86-4e06-926e-56bc3a072275" />


---

## 📈 Sample Prediction

```python
Input:
{
    "Experience": 5,
    "Age": 30,
    "Education": "Masters",
    "Location": "Urban",
    "Job_Title": "Engineer",
    "Gender": "Male"
}

Output:
Predicted Salary: ₹72,453.26
```

---

## 📂 Project Structure

```
employee-salary-prediction/
│
├── SalaryPrediction.ipynb        # Jupyter notebook with full code
├── salary_prediction_data.csv    # Dataset
├── README.md                     # Project documentation
├── requirements.txt              # Python libraries
├── images/                       # Screenshots for README
│   ├── dataset_preview.png
│   ├── salary_distribution.png
│   ├── model_score.png
│   └── sample_prediction.png
```

---

## 📌 How to Run

1. Clone this repo
```bash
git clone https://github.com/your-username/employee-salary-prediction.git
cd employee-salary-prediction
```

2. Install required packages
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 🚀 Future Improvements

- Add more employee features like performance rating or skills
- Try advanced models like Random Forest, XGBoost
- Deploy the model using Streamlit or Flask
- Add a web interface for HR teams

---

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/mrsimple07/salary-prediction-data)
- Scikit-learn Documentation
- Towards Data Science articles

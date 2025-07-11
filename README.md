# salary-prediction-ensemble

This project predicts employee salaries using ensemble learning methods such as Random Forest and Gradient Boosting. The goal is to build an accurate model for salary prediction and gain insights from the data through visualizations.

---

## 📊 Dataset

- **Source**: Kaggle - [Data Science Job Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
- **File Used**: `ds_salaries.csv`

---

## ⚙️ Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 📌 Project Structure

- `notebook/salary_prediction.ipynb`: Full code implementation
- `data/ds_salaries.csv`: Dataset file
- `README.md`: Project overview
- `requirements.txt`: Python libraries used

---

## 🚀 Implementation Steps

1. Data loading and preprocessing
2. Exploratory Data Analysis (EDA) & Visualizations
3. Feature encoding
4. Model building using Random Forest and Gradient Boosting
5. Voting Regressor ensemble model
6. Evaluation using R² and MSE
7. Visual analysis of predictions

---

## 📈 Sample Visualizations

- Salary Distribution
- Average Salary by Year
- Actual vs Predicted Salary

---

## ✅ Results

- **R² Score**: 0.6304795635278324
- **Mean Squared Error**: 1416212634.939202

---

## 📎 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/salary-prediction-ensemble.git

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebook/salary_prediction.ipynb

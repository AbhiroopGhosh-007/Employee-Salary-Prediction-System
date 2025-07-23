# 🧠 Employee-Salary-Prediction-System
 
This project is a machine learning web app that predicts whether an employee earns **more than 50K** or **less than or equal to $50K** per year based on personal and professional attributes such as age, education, occupation, and working hours.
This project is part of the Edunet Foundation Internship , in collaboration with IBM SkillsBuild and AICTE.

## 🔍 Problem Statement

Predict income classes (<=50K or >50K) using the **Adult Census Income Dataset**. This is a binary classification problem widely used in predictive modeling.

---

## 📊 Features Used

- Age  
- Education Level  
- Job Role (Occupation)  
- Hours Worked Per Week  
- Years of Experience  
- Other features from dataset (for batch prediction):  
  - Marital Status  
  - Relationship  
  - Race  
  - Gender  
  - Capital Gain / Loss  
  - Workclass  
  - Native Country  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Google Colab**
- **Streamlit** (for Web App)
- **Joblib** (for saving model)
- **GitHub** (for version control)

---

## 🚀 How to Run Locally

1. Clone the repo

git clone  
https://github.com/AbhiroopGhosh-007/Employee-Salary-Prediction-System.git cd Employee-Salary-Prediction-System

2. Install dependencies

 !pip install streamlit

3. Start the app

streamlit run app.py

---

## 📂 Project Structure

. ├── app.py                    # Streamlit web app ├── app.py     # Google Colab for model building ├── best_model.pkl,employee salary prediction.ipynb        # Trained ML model ├── cleaned_adult.csv                # Python dependencies └── README.md               

---

## 🧪 Model Used

- **Random Forest Classifier**  
- Accuracy: ~85%  
- Feature Encoding: LabelEncoder / OneHotEncoder  
- Scaling: StandardScaler (if needed)

---

## 🖥️ Web App Features

- ✅ Predict salary class for a single input (via sliders and dropdowns)
- 📁 Batch prediction using CSV upload
- 📥 Download predictions as CSV

---

📚 Dataset

Adult Income Dataset from UCI Machine Learning Repository



---
👤 Author

Brijeshrath67

BTech CSE (AI & ML)


---

🌟 Acknowledgements

UCI ML Repository

Streamlit Documentation

Scikit-learn Docs



---

📌 Future Improvements

Add cloud deployment (e.g., Streamlit Cloud, Render, or HuggingFace)

Model performance dashboard

Hyperparameter tuning & model comparison



---

📄 License

This project is licensed under the MIT License.

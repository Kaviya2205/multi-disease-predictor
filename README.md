```markdown
# 🧬 Multi-Disease Prediction Using Machine Learning

A comprehensive machine learning project designed to predict three major health conditions—**Diabetes**, **Heart Disease**, and **Parkinson’s Disease**—based on user input data. This system aims to assist healthcare professionals and individuals in early diagnosis and preventive care using intelligent algorithms.

---

## 🎯 Objectives

- Predict the presence of **Diabetes**, **Heart Disease**, and **Parkinson’s Disease** using medical data.
- Build a unified system that accepts user inputs and gives disease-wise predictions.
- Provide real-time, interactive access through a simple and effective web interface.

---

## 🧠 Technologies Used

- **Python**  
- **Pandas, NumPy** – Data analysis  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models  
- **Streamlit** – Web application interface  
- **Google Colab** – Model development & experimentation  

---

## 🏥 Diseases Covered

### 1. **Diabetes**
- Dataset: PIMA Indian Diabetes Dataset
- Model: Logistic Regression / Random Forest
- Accuracy: 73%

### 2. **Heart Disease**
- Dataset: Cleveland Heart Disease Dataset
- Model: Random Forest Classifier
- Accuracy: 87%

### 3. **Parkinson’s Disease**
- Dataset: UCI Parkinson’s Dataset
- Model: SVM or XGBoost
- Accuracy: 92%

---

## 🖥️ Streamlit Web App

The project includes a Streamlit-based web interface where users can input medical parameters and get instant predictions.

### 💻 Run the App Locally

```bash
git clone https://github.com/your-username/multi-disease-prediction.git
cd multi-disease-prediction
pip install -r requirements.txt
streamlit run app.py
```

---

## 📁 Project Structure

```
multi-disease-prediction/
│
├── diabetes_model.pkl             # Trained diabetes model
├── heart_disease_model.pkl        # Trained heart disease model
├── parkinsons_model.pkl           # Trained Parkinson’s model
├── app.py                         # Streamlit application
├── README.md                      # Project description
├── requirements.txt               # Python dependencies
├── images/                        # App screenshots
└── notebooks/                     # Jupyter notebooks for each model
```

---

## 📊 Model Performance Summary

| Disease        | Accuracy | Precision (1) | Recall (1) | F1-Score (1) |
|----------------|----------|----------------|-------------|----------------|
| Diabetes       | 73%      | 0.62           | 0.65        | 0.64           |
| Heart Disease  | 87%      | 0.90           | 0.88        | 0.89           |
| Parkinson’s    | 92%      | 0.94           | 0.97        | 0.95           |

---


## 🚀 Future Improvements

- Add more diseases to the platform (e.g., kidney disease, liver disease)
- Integrate with medical APIs for real-time records
- Deploy using Docker or on cloud platforms (Heroku, AWS, etc.)
- Add user authentication and history tracking

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues, suggest features, or submit pull requests.

---

## 📜 License

This project is for academic and educational purposes only.

---


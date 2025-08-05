# 🏥 Health Insurance Cost Predictor

A web-based machine learning application built using **Streamlit** that estimates the cost of health insurance for individuals based on factors such as age, income, BMI, medical history, lifestyle, and more.

🚀 **Live App**: [Click to Launch](https://dewanshu-ml-project-health-insurance-predictor.streamlit.app/)  

---

## 🔍 Key Highlights

- 📈 Predicts insurance premiums using pre-trained ML models.
- 🧠 Takes into account demographics, lifestyle, risk profile, and insurance preferences.
- 🧑‍🔬 Uses separate models for different age brackets (≤ 25 and > 25).
- 🌐 Interactive user interface designed with Streamlit.

---

## 🧩 User Input Parameters

| Parameter              | Range / Options                                  |
|------------------------|--------------------------------------------------|
| **Age**                | 18 to 100                                        |
| **Dependents**         | 0 to 20                                          |
| **Income (Lakhs)**     | 0 to 200                                         |
| **Genetic Risk Score** | 0 to 5                                           |
| **Plan Type**          | Bronze / Silver / Gold                           |
| **Employment**         | Salaried / Self-Employed / Freelancer            |
| **Gender**             | Male / Female                                    |
| **Marital Status**     | Married / Unmarried                              |
| **BMI Category**       | Underweight / Normal / Overweight / Obesity      |
| **Smoking Habit**      | No Smoking / Occasional / Regular                |
| **Region**             | Northwest / Southeast / Northeast / Southwest    |
| **Medical History**    | Multiple conditions (selectable combinations)    |

📚 Tech Stack
streamlit – UI framework
pandas / numpy – Data manipulation
scikit-learn – Model training and preprocessing
joblib – Model serialization

📁 Project Layout
bash
Copy
Edit
ml_project_health_insurance_predictor/
│
├── main.py                  # Streamlit app entry point
├── prediction_helper.py     # Contains preprocessing & prediction logic
├── requirements.txt         # Project dependencies
├── README.md                # Documentation
├── Artifacts/               # Folder containing trained models
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib

🤝 Acknowledgments
This project is developed as part of the Codebasics ML Bootcamp by codebasics.io.
It was extended and customized to suit real-world deployment using Streamlit Cloud.

✨ Connect with Me
Dewanshu Nagi
🔗 https://www.linkedin.com/in/dewanshu-nagi

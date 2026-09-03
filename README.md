# 🧠 Mental Health Score Prediction

An AI/ML-powered **Student Wellness Analytics** web application that predicts a mental-health score on a **0–10 scale** based on lifestyle, academic, digital-usage, sleep, physical activity, and stress-related factors.

🔗 **Live Demo:** https://mental-health-score-2-51hd.onrender.com/

---

## 📌 Project Overview

Mental health and overall well-being can be influenced by several lifestyle and academic factors.

This project uses **Machine Learning** to analyze user-provided wellness information and generate an estimated mental-health score between **0 and 10**.

The application provides a simple and interactive interface where users can enter relevant information and receive a prediction in real time.

> ⚠️ **Disclaimer:** This application is developed for educational and informational purposes only. It is not a medical or clinical diagnostic tool.

---

## 🚀 Features

* 🧠 Mental-health score prediction
* 📊 Lifestyle and wellness-based analysis
* 🎓 Student-focused inputs
* 📱 Digital usage analysis
* 😴 Sleep and physical activity factors
* 📚 Academic/study-related factors
* 😰 Perceived stress consideration
* ⚡ Real-time prediction through a web interface
* 🌐 Deployed and accessible online

---

## 📥 Input Features

The application considers several factors related to student lifestyle and wellness, including:

* Age
* Academic level
* Study hours
* Screen time
* Phone usage
* Sleep
* Physical activity
* Perceived stress
* Other relevant lifestyle factors

These inputs are processed by the machine-learning pipeline to generate the predicted score.

---

## 🤖 Machine Learning Workflow

The project follows a standard machine-learning workflow:

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Integration
      ↓
Web Application
      ↓
Deployment
```

---

## 🛠️ Technologies Used

### Programming

* Python

### Machine Learning

* Scikit-learn
* Pandas
* NumPy

### Data Analysis & Visualization

* Matplotlib
* Seaborn

### Web Application

* Python-based web application
* Fastapi
* Pydantic

### Deployment

* Render

---

## 💻 Project Structure

```text
Mental-Health-Score/
│
├── app.py
├── model/
│   └── trained_model.pkl
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── requirements.txt
├── README.md
└── ...
```

> The exact structure may vary depending on the final project files.

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/AbubakarSiddiqueAI/Mental_Health_Score
```

### 2. Navigate to the project directory

```bash
cd (https://github.com/AbubakarSiddiqueAI/Mental_Health_Score)
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

Then open:

```text
http://localhost:5000
```

---

## 🌐 Live Application

The application is deployed on Render and can be accessed here:

**Live Demo:**
https://mental-health-score-2-51hd.onrender.com/

---

## 📊 Example Workflow

1. Open the web application.
2. Enter the required student wellness information.
3. Submit the form.
4. The trained machine-learning model processes the inputs.
5. The application displays the predicted mental-health score.

---

## 🎯 Learning Objectives

This project helped me gain practical experience with:

* Machine Learning workflow
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Python-based ML development
* Integrating ML models into web applications
* Deploying ML applications
* Building user-friendly prediction interfaces

---

## 🔮 Future Improvements

Possible improvements include:

* Adding multiple machine-learning models for comparison
* Improving model performance through hyperparameter tuning
* Adding interactive data visualizations
* Providing personalized wellness recommendations
* Adding model explainability using SHAP
* Improving UI/UX
* Adding authentication and user history
* Containerizing the application with Docker
* Implementing continuous deployment

---

## ⚠️ Disclaimer

This project is intended for **educational and research purposes**.

The predicted score should not be interpreted as a medical diagnosis, psychological assessment, or professional health advice.

If someone is experiencing mental-health difficulties, they should consult a qualified healthcare professional.

---

## 👨‍💻 Author

**Abubakar Siddique**

AI/ML Engineer | Python | Machine Learning | Deep Learning

* GitHub: [https://github.com/AbubakarSiddiqueAI]

---

## ⭐ Project

If you found this project interesting, consider giving the repository a ⭐.

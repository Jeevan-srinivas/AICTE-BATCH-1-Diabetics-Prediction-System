# 🩺 Diabetes Prediction System

## Overview

The Diabetes Prediction System is a Machine Learning web application that predicts whether a patient is likely to have diabetes based on several medical parameters. The application uses a trained Support Vector Machine (SVM) model and provides predictions through a user-friendly Flask web interface.

---

## Features

* Predict diabetes risk using Machine Learning
* Interactive web interface built with Flask
* Real-time prediction results
* Responsive and user-friendly design
* Deployable on Render and other cloud platforms

---

## Technologies Used

### Backend

* Python
* Flask

### Machine Learning

* Scikit-Learn
* Support Vector Machine (SVM)
* Joblib

### Frontend

* HTML5
* CSS3

### Data Processing

* NumPy
* Pandas

---

## Input Parameters

The model uses the following health-related attributes:

1. Pregnancies
2. Glucose Level
3. Blood Pressure
4. Skin Thickness
5. Insulin
6. BMI (Body Mass Index)
7. Diabetes Pedigree Function
8. Age

---

## Project Structure

```text
Diabetes-Prediction-System/
│
├── app.py
├── diabeties.pkl
├── requirements.txt
├── Procfile
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction-System.git
cd Diabetes-Prediction-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Sample Test Input

### Likely Non-Diabetic

```text
Pregnancies: 1
Glucose: 95
Blood Pressure: 70
Skin Thickness: 20
Insulin: 85
BMI: 23.5
Diabetes Pedigree Function: 0.25
Age: 25
```

### Likely Diabetic

```text
Pregnancies: 8
Glucose: 180
Blood Pressure: 95
Skin Thickness: 35
Insulin: 220
BMI: 38.5
Diabetes Pedigree Function: 1.2
Age: 55
```

---

## Machine Learning Model

* Algorithm: Support Vector Machine (SVM)
* Library: Scikit-Learn
* Model Storage: Joblib (.pkl)

### Prediction Classes

| Output | Meaning      |
| ------ | ------------ |
| 0      | Non-Diabetic |
| 1      | Diabetic     |

---

## Deployment

This application can be deployed on:

* Render
* Railway
* PythonAnywhere
* Fly.io

### Render Deployment

Build Command:

```bash
pip install -r requirements.txt
```

Start Command:

```bash
gunicorn app:app
```

---

## Future Enhancements

* Prediction confidence score
* Interactive health dashboard
* Patient record management
* Model performance visualization
* Advanced medical recommendations

---

## Author

**Jeevan Srinivas**

Machine Learning Enthusiast | Python Developer | GATE CS 2026 Aspirant

---

## License

This project is developed for educational and portfolio purposes.

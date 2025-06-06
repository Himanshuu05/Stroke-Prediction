# 🧠 Stroke Prediction Web App

A full-stack web application that predicts the likelihood of a stroke based on user inputs. Built using **React** for the frontend, **Flask** for the backend, and a **machine learning model** trained on real stroke-related health data.

---

## 🚀 Demo

> 🔮 Enter health information like age, gender, glucose level, etc., and get an instant prediction of stroke risk.

---

## 📌 Features

- 🖥️ User-friendly UI with styled form and animations
- ⚙️ React-based dynamic input form
- 🧠 Flask API connected to an ML model
- 📊 Machine learning pipeline with preprocessing, SMOTE, and LDA
- 🔄 Real-time JSON communication between frontend and backend

---

## 🛠️ Tech Stack

### Frontend
- React.js
- CSS3

### Backend
- Flask (Python)
- Flask-CORS

### Machine Learning
- Scikit-learn
- imbalanced-learn (SMOTE)
- joblib (model serialization)

---

## 📂 Project Structure

stroke-prediction-app/
│
├── frontend/
│ ├── App.js # React form component
│ ├── App.css # Styling and animations
│ ├── index.js # Entry point
│
├── backend/
│ ├── app.py # Flask server with prediction route
│ ├── training.py # Model training & saving script
│ ├── stroke-data.csv # Dataset
│ ├── stroke_prediction_model.joblib # Trained ML pipeline

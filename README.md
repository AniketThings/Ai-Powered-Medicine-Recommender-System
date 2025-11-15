# 🩺 AI-Powered Medical Recommender System

This is a Flask-based web application that leverages machine learning and natural language processing to provide *personalized medical content* based on user symptoms. The system predicts potential diseases using an SVC (Support Vector Classifier) model and recommends *medications, workouts, diets*, and other health-related tips.

---

## 📌 Features

* 🔍 *Disease Prediction* using SVC and multiple medical datasets
* 🗣 *Voice-to-Text NLP* for symptom input
* 🧠 *Multi-Stage Recommendation Engine* for generating medical advice
* 📊 *>85% Accuracy* in real-world test scenarios
* 🔄 Integrated *5+ healthcare datasets* for robust learning
* 💡 Personalized health tips including *medications, diets, and workouts*

---

## 🛠 Tech Stack

* *Languages & Libraries:* Python, Pandas, NumPy, Scikit-learn, Flask
* *NLP:* Speech Recognition for voice input
* *Modeling:* SVC (Support Vector Classifier)
* *Frontend:* HTML, CSS (basic Flask templates)
* *Deployment:* Localhost / Web server

---

## 🧪 How It Works

1. User inputs symptoms via *text or voice*
2. The backend uses an *SVC classifier* to predict the possible disease
3. Based on the disease, the system fetches relevant:

   * Medication recommendations
   * Suggested diets
   * Daily workout plans
4. The results are returned in a clean, user-friendly dashboard

---

## 🚀 Setup Instructions

1. Clone the repo:

   bash
   git clone https://github.com/AniketThings/medical-recommender-system.git
   cd medical-recommender-system
   

2. Install dependencies:

   bash
   pip install -r requirements.txt
   

3. Run the app:

   bash
   python app.py
   

4. Open http://localhost:5000 in your browser to use the application

---

## 📂 Dataset Info

* Aggregated from *5+ public healthcare datasets*
* Preprocessed and cleaned using Pandas and NumPy
* Features include symptoms, disease labels, recommended treatments, diets, and exercises

---

## 📈 Accuracy

* Model achieved an accuracy of *85%+* during validation on combined healthcare datasets

---

## 📃 License

This project is for educational and non-commercial use. Medical suggestions are *not certified* and should not be used as a replacement for professional medical advice.


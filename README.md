# 🩺 Health Symptom Assistant

An AI-based health symptom analysis application that allows users to enter their symptoms and receive possible health conditions, general concerns, severity information, and recommended next steps.

## ⚠️ Medical Disclaimer

This project is an educational software prototype. It does not provide a medical diagnosis and should not be used as a substitute for a qualified healthcare professional or emergency medical care.

## 🚀 Features

* Enter symptoms using natural language
* Analyze symptoms using NLP
* Find possible matching health conditions
* Display symptom-match scores
* Provide general severity information
* Identify potentially serious warning symptoms
* Provide general self-care information
* Provide guidance about when to seek medical attention
* Simple web interface using Gradio
* Runs directly in Google Colab

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF
* Cosine Similarity
* Gradio
* Google Colab

## 🧠 How It Works

```text
User Symptoms
      ↓
Text Cleaning
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Compare With Symptom Dataset
      ↓
Possible Conditions
      ↓
Risk & Concern Information
      ↓
Health Information Report
```

## 📊 Example

User enters:

```text
fever, cough, sore throat and body ache
```

The system compares the entered symptoms with the symptom information in the dataset and returns possible matching conditions.

The similarity score is a text-matching score and should NOT be interpreted as the probability that a user has a disease.

## 💻 Running the Project

### Option 1 — Google Colab

Open the notebook in Google Colab and execute the cells from top to bottom.

### Option 2 — Local Python Environment

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/health-symptom-assistant.git
```

Go into the project:

```bash
cd health-symptom-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Google Colab.

## 📁 Project Structure

```text
health-symptom-assistant/
│
├── health_symptom_assistant.ipynb
├── data/
│   └── Dataset.csv
├── requirements.txt
└── README.md
```

## 🔮 Future Improvements

* Add a larger medically reviewed dataset
* Add more symptoms and conditions
* Add symptom selection using checkboxes
* Add patient history
* Add multilingual support
* Add explainable AI
* Add doctor/healthcare-provider review
* Add downloadable health reports
* Add secure database integration
* Improve emergency warning detection
* Deploy the application as a web application

## 👨‍💻 Author

Your Name

## 📌 Disclaimer

This application is intended for educational and research purposes only. It is not intended to diagnose, treat, cure, or prevent any disease or medical condition.

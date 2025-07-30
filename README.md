# 🧬 Pathodust: An Offbeat Disease Predictor for India

**Pathodust** is a machine learning–powered disease prediction tool crafted for the Indian healthcare context. It takes in a list of symptoms and attempts to predict the most likely disease, based on a curated dataset that includes regionally relevant illnesses like Dengue, Malaria, Typhoid, Chikungunya, Tuberculosis, and more.

This isn’t your typical health app. It’s a sharp, minimal, and slightly weird prototype — designed to be expanded into smarter triage systems, AI health bots, or offline diagnostic tools for underserved regions.

---

## 🔍 Features

- 🧠 Predict diseases based on 5 input symptoms
- 🌏 India-focused dataset with high-prevalence illnesses
- 📁 Includes disease stages (Mild / Moderate / Severe)
- 💡 Ready for ML model training & API/GUI integration

---

## 📂 Project Structure
 Pathodust/
├── disease.csv # Symptom-disease dataset
├── predictor.py # Core logic for prediction (to be built)
├── README.md # This file
└── requirements.txt # Dependencies (optional)

---

## 📊 Dataset: `disease.csv`

A handcrafted CSV file containing:
- 5 primary symptoms per disease
- Disease name
- Stage/severity (Mild, Moderate, Severe)

This dataset can be used to train basic classifiers (like Decision Trees, Random Forests, etc.) or prototype rule-based systems.

---

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/geeekgeeez/Pathodust.git
   cd Pathodust

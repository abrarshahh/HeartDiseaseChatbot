# Heart Disease Chatbot

A multi-component project that integrates a **conversational chatbot**, a **heart disease prediction model**, and **Tableau visualizations** to provide insights and interactive assistance related to heart disease.  
This repository is intended for educational exploration of machine learning, NLP chat interfaces, and data visualization workflows.

---

## 🧠 Project Overview

Cardiovascular disease remains one of the leading causes of morbidity globally. Integrating conversational AI with predictive health models and visual analytics can help users better understand risks and receive tailored responses. :contentReference[oaicite:2]{index=2}

This project consists of three major components:
1. **ChatBot** – A conversational interface that interacts with users about heart disease topics and potentially guides them through symptom assessment.
2. **Model** – A machine learning/deep learning model that predicts heart disease outcomes using clinical or symptom data.
3. **Tableau** – Visual dashboards and reports for exploring heart disease data and model results.

---

## 📁 Repository Structure

```text
HeartDiseaseChatbot/
├── ChatBot/               # Chatbot codebase (Python, NLP scripts, UI logic)
├── Model/                 # Pretrained model files and training scripts
├── Tableau/               # Tableau dashboard files and visualization assets
└── README.md              # Project documentation
```

---

## 🛠 Installation & Setup

1. Clone the repository.

   ```bash
   git clone https://github.com/abrarshahh/HeartDiseaseChatbot.git
   cd HeartDiseaseChatbot

2. Create a Python environment.

   ```bash
   python3 -m venv venv
   source venv/bin/activate

3. Install Dependencies

   ```bash
   pip install flask tensorflow scikit-learn nltk

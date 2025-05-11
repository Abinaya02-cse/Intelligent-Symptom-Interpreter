

## 🧠 Intelligent Symptom Interpretation System

The **Intelligent Symptom Interpretation System** is a healthcare-focused chatbot designed to bridge the gap between informal symptom descriptions and medically recognized conditions. It uses NLP techniques to interpret vague user input, extract symptoms using Named Entity Recognition (NER), and map those symptoms to likely medical conditions through an ontology-driven process.

---

## 📄 Project Abstract

Many patients describe symptoms using non-clinical language like “I feel dizzy when I get up,” making it hard for automated systems to understand. This system applies NLP to:
- Preprocess and clean user input,
- Identify symptoms via NER,
- Map symptoms to probable conditions using an ontology,
- And respond with health-related suggestions in natural language.

This project showcases a practical application of NLP in health informatics and can be adapted for digital triage or symptom-checking interfaces.

---

## 📘 Project Overview

- Understands vague or non-clinical symptom expressions.
- Built for use in hospitals and healthcare triage systems.
- Interprets symptoms using a rule-based NER system.
- Maps symptoms to medical conditions via a predefined ontology.
- Offers a chatbot-style interaction interface.

---

## 🎯 Objectives

- 🧾 Interpret vague symptom descriptions.
- 🧹 Use NLP to clean and tokenize text.
- 🔍 Apply rule-based NER to extract symptoms.
- 🗺 Map symptoms to conditions using an ontology.
- 💬 Generate clear, human-readable chatbot responses.

---

## 🧩 Components

| Module              | Function                                 |
|---------------------|------------------------------------------|
| `app.py`            | Main chatbot loop                        |
| `preprocessing.py`  | Text cleaning and lemmatization using spaCy |
| `ner_module.py`     | Rule-based medical symptom extraction    |
| `ontology_mapper.py`| Maps symptoms to probable conditions     |
| `chatbot_response.py` | Generates chatbot replies               |

---

## 🗃 Example Input & Output

![Screenshot 2025-05-11 162112](https://github.com/user-attachments/assets/906d786a-90f7-4307-90ac-3152800afdd6)

---

## 🛠 How to Run the Project

### ✅ Prerequisites
- Python 3.8+
- `spaCy` and the English NLP model (`en_core_web_sm`)

---

### 💻 Installation Instructions

#### 🖥 Windows

1. Install Python from [python.org](https://www.python.org/).
2. Open **Command Prompt**.
3. Run:
   ```bash
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
   python app.py
🍏 macOS
Install Python.

Open Terminal.

Run:pip install -r requirements.txt
python -m spacy download en_core_web_sm
python app.py
🐧 Linux
Ensure Python is installed.

Open Terminal.

Run:pip install -r requirements.txt
python -m spacy download en_core_web_sm
python app.py

📂 Project Files
app.py – Main script to run the chatbot

preprocessing.py – Text preprocessing using spaCy

ner_module.py – Extracts key medical symptoms

ontology_mapper.py – Maps symptoms to medical conditions

chatbot_response.py – Builds final chatbot replies

requirements.txt – Project dependencies

README.md – Project documentation

🎞 Presentation Slides
📽 View Presentation Slides (Intelligent_Symptom_Interpretation_System.pptx)

🧠 Future Improvements
Integrate medical NER using SciSpacy or Med7

Use real-world ontologies like SNOMED CT or ICD-10

Apply deep learning for improved language understanding

Develop a web-based UI using Flask or Streamlit

👨‍⚕️ Disclaimer
This chatbot is not a diagnostic tool. It is intended solely for educational and demonstration purposes. Always consult a qualified healthcare provider for medical advice.

📜 License
MIT License – For academic and non-commercial use.



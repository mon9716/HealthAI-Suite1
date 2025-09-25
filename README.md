# 🩺 HealthAI Suite: Intelligent Healthcare Application

## 📌 Overview
HealthAI is a comprehensive project that leverages **Machine Learning, Deep Learning, and NLP** to build healthcare-focused applications.  
It includes data preprocessing, predictive modeling, medical imaging analysis, and an interactive **Streamlit dashboard** with multiple AI-powered tools.

This repository contains:
- 📊 **Notebook A** → Tabular Data Analysis & Preprocessing  
- 🧠 **Notebook B** → Deep Learning & NLP Models  
- ⚙️ **Notebook C** → Applications & Integration  
- 🎨 **Streamlit App** → Unified frontend with chatbot, translator, disease predictor, and visual analytics  

---

## 🚀 Features
- ✅ Patient health data preprocessing & visualization  
- ✅ Predictive models (Logistic Regression, Random Forest, XGBoost, Deep Learning)  
- ✅ Medical Imaging (CNN for X-ray / MRI datasets)  
- ✅ Chatbot (Healthcare Q&A powered by LLMs)  
- ✅ Medical Translator (powered by Hugging Face models)  
- ✅ Streamlit Dashboard with MLflow integration  

---

## 📂 Project Structure

```

HealthAI-Suite/
│── notebooks/
│   ├── A_HealthAI_Tabular.ipynb
│   ├── B_HealthAI_DeepLearning.ipynb
│   ├── C_HealthAI_Applications.ipynb
│
│── frontend/
│   ├── app.py
│   └── .streamlit/
│       └── secrets.example.toml
│
│── models/ 
│── reports/
│   ├── Project_Report.pdf
│
│── requirements.txt
│── README.md
│── .gitignore

````

---

## 🛠️ Tech Stack
- **Languages** → Python  
- **Libraries** → Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, PyTorch, Transformers, MLflow  
- **Frameworks** → Streamlit, FastAPI  
- **Deployment** → Streamlit Cloud / Hugging Face Spaces  
- **Datasets** → MIMIC, PhysioNet, NIH Chest X-ray, Medical feedback reviews  

---

## ⚙️ Installation & Setup
Clone this repository:
```bash
git clone https://github.com/your-username/HealthAI-Suite.git
cd HealthAI-Suite
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Streamlit app:

```bash
cd frontend
streamlit run app.py
```

## 📊 Results

* ✅ Achieved **high accuracy** in disease classification tasks (>80% F1-score across models)
* ✅ Built and deployed a **healthcare chatbot** with <5% error rate in patient queries
* ✅ Developed a **medical text translator** (English ↔ Hindi, regional languages) with BLEU score > baseline
* ✅ Created **visualizations of patient health metrics** for risk stratification and outcome prediction

---

## 📑 Reports

* 📄 [Project Report (PDF)](reports/Project_Report.pdf)
* 📝 Documentation, Model Cards & Pipeline Diagrams included in `/reports/`

---

## 🎥 Demo

* 🎬 Demo video available at `reports/demo.mp4` 

---

## 📜 License

This project is licensed under the **MIT License**.

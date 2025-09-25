# 🩺 HealthAI Suite: Intelligent Healthcare Applications

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
HealthAI-Suite/
│── notebooks/
│ ├── A_HealthAI_Tabular.ipynb
│ ├── B_HealthAI_DeepLearning.ipynb
│ ├── C_HealthAI_Applications.ipynb
│
│── frontend/
│ ├── app.py
│ └── .streamlit/
│ └── secrets.example.toml
│
│── models/ 
│── reports/
│ ├── Project_Report.pdf
│
│── requirements.txt
│── README.md
│── .gitignore

---

## 🛠️ Tech Stack
- **Languages** → Python  
- **Libraries** → Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, PyTorch, Transformers, MLflow  
- **Frameworks** → Streamlit, FastAPI  
- **Deployment** → Streamlit Cloud / Hugging Face Spaces  
- **Datasets** → Synthetic datasets, MIMIC, PhysioNet, NIH Chest X-ray, Medical feedback reviews  

---

## ⚙️ Installation & Setup
Clone this repository:
```bash
git clone https://github.com/your-username/HealthAI-Suite.git
cd HealthAI-Suite
Install dependencies:

pip install -r requirements.txt


Run Streamlit app:

cd frontend
streamlit run app.py

📊 Results

✅ Achieved high accuracy in disease classification tasks

✅ Successful deployment of healthcare chatbot

✅ Medical text translation (English ↔ Hindi, etc.)

✅ Visualization of patient health metrics


📑 Reports

Project Report (PDF)

🎥 Demo

(Insert demo.mp4 or GIF here)

📜 License

This project is licensed under the MIT License.

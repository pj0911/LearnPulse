# 📚 LearnPulse: PDF-Based MCQ Generator

**LearnPulse** is an AI-powered Streamlit web app that generates multiple-choice questions (MCQs) from any uploaded PDF document.  
It helps students, educators, and professionals quickly create quizzes and test their knowledge with AI-evaluated answers and explanations.

---

## ✨ Features

✅ Upload any PDF (e.g., lecture notes, reports, health or legal docs)  
✅ Automatically generate 5/10 MCQs with 4 options each  
✅ Includes correct answer with explanations  
✅ Interactive quiz interface with answer validation  
✅ Final score display  
✅ Export all questions + answers to a downloadable DOCX file  
✅ Powered by **LangChain + Groq LLM (LLaMA3-70B)**

---
---

## 🚀 Live Demo

👉 [LearnPulse](https://learnpulse.streamlit.app)  

*(Replace the link above with your actual Streamlit Cloud / Render deployment URL)*  

---
## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
   git clone https://github.com/your-username/LearnPulse.git
   
   cd LearnPulse
```
### 2. Install Dependencies
```bash
 -pip install -r requirements.txt
```
### 3. Add Groq API Key
```bash
 -Create a .streamlit/secrets.toml file and add:

GROQ_API_KEY = "your-groq-api-key-here"
```
💡 Get your API key from: https://console.groq.com/keys

### 4. Run the App
```bash
 -streamlit run app.py
```




### 💡 Use Cases
1. 📖 Self-study from lecture PDFs 

2. 🏥 Generating quizzes from document


3. 📑 Generating scores for analysis.
   
4. 👨‍🏫 Teaching assistants auto-generating tests


### 🛠 Built With
🐍 Python

🔥 LangChain

🤖 Groq (LLaMA3-70B model)

🧠 Streamlit

📄 PyPDF2

📤 python-docx

### 👩‍💻 Author
Pranav Jain
📧 Email: jainpranav3882@gmail.com

For queries, support, or collaboration — feel free to reach out!

# 🔍 LangChain Chat with Search

An AI-powered chat application built using **LangChain** and **Streamlit** that allows users to ask questions just like a search engine.  
It can answer **general questions** as well as queries related to **research papers**, Wikipedia, and web-based knowledge.

---

## ✨ Features

- 💬 Chat-based question answering
- 🔎 Search-like behavior for research and general topics
- 📄 Useful for understanding research papers
- ⚡ Powered by Groq LLMs
- 🎨 Simple and clean Streamlit UI
- 🔐 API key configuration via Settings panel

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- Streamlit  
- Groq API  

---

## 📂 Project Structure

.
├── app.py
├── requirements.txt
├── README.md


---

## 🚀 Getting Started

Follow the steps below to run the project locally.

---

### 1️⃣ Create a Virtual Environment

python -m venv venv
Activate the virtual environment:

## Windows

venv\Scripts\activate


## macOS / Linux

source venv/bin/activate

### 2️⃣ Install Dependencies
pip install -r requirements.txt

### 3️⃣ Run the Application
streamlit run app.py

### 4️⃣ Open the UI

## A browser window will open automatically

If not, open the URL shown in the terminal (usually http://localhost:8501)

## ⚙️ Configuration
- Open the application UI
- Go to the Settings panel on the left
- Enter your Groq API Key
- Save the key

## You’re now ready to use the chatbot.

### 🧪 How to Use
#### You can ask:
#####  General questions
- What is machine learning?
  
##### Research paper questions
- Explain the paper Attention Is All You Need

##### Technical concepts
- What is task decomposition in AI agents?

### The chatbot behaves like a search engine, retrieving and explaining information from research papers and web sources.

## 🔐 Notes
- Do NOT hardcode API keys
- Keep your Groq API key private, enter them in the ui
- Avoid pushing .env files to GitHub

## 🚧 Future Enhancements
- Conversation memory
- Source citations
- PDF-based RAG support
- Cloud deployment
- Multi-model support

## 📄 License
### This project is intended for learning and experimentation.
### ⭐ If you find this project useful, consider giving it a star!
---

## If you want, I can:
- Make it **resume / portfolio optimized**
- Add **screenshots section**
- Add **badges (Python, Streamlit, LangChain)**
- Rewrite it in a **more professional / enterprise style**

## Just tell me 😊




# Azure OpenAI Chatbot with Python & Flask

A simple real-time chatbot built with **Python (Flask)** and **Azure OpenAI GPT**.

---

## 🚀 Features
- Real-time chat with GPT model hosted on Azure
- Web interface (HTML + JavaScript)
- Environment variables for security
- Easy to extend with conversation memory

---

## 🛠 Tech Stack
- Python 3
- Flask
- HTML, CSS, JavaScript
- Azure OpenAI Service
- dotenv for environment variables

---

## 📂 Project Structure


[ User Browser ]
      │  (message: "Hello")
      ▼
[ index.html + JS ]
      │  HTTP POST /chat
      ▼
[ Flask Server (app.py) ]
      │  AzureOpenAI SDK call
      ▼
[ Azure OpenAI API ]
      │  (Processes with gpt-35-turbo)
      ▼
[ Flask Server ]
      │  JSON { reply: "Hi there!" }
      ▼
[ User Browser ]

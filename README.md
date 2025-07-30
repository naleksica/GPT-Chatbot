# 🧠 GPT-4 Chatbot – Flask + OpenAI API

A simple, responsive web-based chatbot that integrates OpenAI’s GPT-4 via API using Flask (Python) and HTML/JS frontend. Built as a quick AI portfolio piece to demonstrate real-world API integration, full-stack capability, and hands-on AI experimentation.

---

## 🚀 Features

- 🔌 GPT-4 integration via OpenAI’s API
- 🖥️ Clean frontend UI with real-time chat experience
- 🌐 Flask-powered Python backend with REST endpoint
- 🧪 Easily expandable (logging, authentication, etc.)
- ✅ Lightweight and beginner-friendly

---

## 🧰 Tech Stack

| Frontend        | Backend       | API          |
|-----------------|---------------|--------------|
| HTML / CSS / JS | Python (Flask)| OpenAI GPT-4 |

---

## 📦 Setup Instructions

### 1. Clone the repository

```
git clone https://github.com/yourusername/gpt-chatbot.git
cd gpt-chatbot
```

### 2. Install dependencies

```
pip install flask openai
```
✅ For OpenAI SDK v1.0 or newer, make sure your code uses the new client syntax.
🛠️ If using legacy syntax (openai.ChatCompletion.create()), run:

```
pip install openai==0.28
```

### 3. Add your OpenAI API key

In app.py, replace:

```
openai.api_key = "YOUR_OPENAI_API_KEY"
```
Or better: set it as an environment variable:

```
export OPENAI_API_KEY=your-key-here
```
And load it in code:

```
openai.api_key = os.getenv("OPENAI_API_KEY")
```

### 4. Run the app

```
python app.py
```
Then open your browser and go to http://localhost:5000

## 💡 Project Goals

This project demonstrates:

  Real-world AI tool integration (GPT-4)

  Full-stack communication between frontend and backend

  Ability to create functional tools from APIs

### ✍️ Author
Nikola Aleksic
Front-End Developer • Full-Stack Enthusiast
🔗 [LinkedIn](https://www.linkedin.com/in/nikola-aleksic-597208259/)

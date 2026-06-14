# 🤖 Smart AI Chatbot

A simple AI-powered chatbot built using **Python**, **Streamlit**, and **Google Gemini API**. The chatbot provides intelligent and natural responses to user queries through an interactive web interface.

## 🎥 Demo Video

Watch the chatbot in action:

[Demo Video](https://youtu.be/Jtk518Z3gyY?si=5tI8CIgotAXILKQZ)


## 🚀 Features

* Interactive chat interface
* AI-generated responses using Google Gemini
* Modern and user-friendly UI
* Secure API key management using environment variables
* Session-based chat history
* Fast and intelligent responses

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Google Gemini API
* python-dotenv

---

## 📂 Project Structure

```text
Smart-AI-Chatbot/
│
├── app.py
├── .env
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-link>
cd Smart-AI-Chatbot
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Create Environment File

Create a `.env` file in the project root directory.

```env
GEMINI_API_KEY=YOUR_API_KEY_HERE
```

### 5. Run the Application

```bash
streamlit run app.py
```

or

```bash
python -m streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## 🤖 Approach Used

This project follows an **API-Based Chatbot Approach**.

User queries are sent to Google's Gemini AI model through the Gemini API. The model processes the input and generates intelligent responses, which are displayed through a Streamlit-based web interface.

### Why API-Based?

* Easy to implement
* Produces intelligent responses
* No model training required
* Suitable for real-world chatbot applications
---

## 📦 Deliverables

* ✅ Functional AI Chatbot
* ✅ Streamlit Web Interface
* ✅ README Documentation
* ✅ Demo Video

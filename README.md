# 🤖 Smart AI Chatbot

A simple AI-powered chatbot built using **Python**, **Streamlit**, and **Google Gemini API**. The chatbot provides intelligent and natural responses to user queries through an interactive web interface.

---

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

## ✨ What Makes This Chatbot Unique?

Unlike traditional rule-based chatbots, Smart AI Chatbot uses a Large Language Model (LLM) to generate dynamic and context-aware responses.

### Key Highlights

* Natural conversations
* AI-powered responses
* Handles a wide variety of questions
* Fast and interactive experience
* Beginner-friendly implementation using modern AI tools

---

## 🧩 Challenges Faced

### 1. Gemini API Integration

**Challenge:** Understanding how to connect the application with the Gemini API.

**Solution:** Used Google's Generative AI Python library and securely stored the API key using environment variables.

### 2. Managing Chat History

**Challenge:** Maintaining previous messages during the chat session.

**Solution:** Implemented Streamlit Session State to store and display conversation history.

### 3. Secure API Key Management

**Challenge:** Preventing accidental exposure of API keys.

**Solution:** Stored the API key in a `.env` file and excluded it using `.gitignore`.

---

## 📸 Demo

A short demonstration video showcasing the chatbot in action is included with the project submission.

### Sample Questions

* What is Artificial Intelligence?
* Explain Machine Learning.
* Tell me a joke.
* What are the benefits of Python?

---

## 📦 Deliverables

* ✅ Functional AI Chatbot
* ✅ Streamlit Web Interface
* ✅ Public GitHub Repository
* ✅ README Documentation
* ✅ Demo Video

---

## 👨‍💻 Author

**Karthik Krishnan**

Pre-Final Year Computer Science and Engineering Student

St. Joseph's College of Engineering and Technology (SJCET), Palai

---

### 🔖 MuLearn Task

**Task:** Build a Simple Chatbot

**Approach Used:** API-Based Chatbot using Google Gemini API

**Hashtag:** `#cl-ai-chatbot`

```
```

# 🌐 Multilingual AI Loan Chatbot — Great Bangalore Hackathon Project

This is a full-stack web application built for the **Great Bangalore Hackathon**.

- 🖼️ Frontend: [Svelte 5](https://svelte.dev/)
- 🧠 Backend: Python (Flask), integrated with [Google Gemini](https://ai.google.dev/), [LangChain](https://www.langchain.com/), and [LangGraph](https://www.langchain.com/langgraph)
- 🎯 Purpose: A multilingual chatbot that helps users get loan-related support using speech/text in multiple Indian languages.

---

## 🧠 Key Features

- Uses **Gemini LLM** to perform language reasoning, RAG, and decision-making.
- **Firebase** is used to store user data and session details.
- **Sarvam AI**, **Google TTS**, **Language Detection**, and **Vertex Embeddings** are used for speech and language support.
- Svelte frontend talks to the Flask backend via REST APIs.
- Built-in **state management** using LangGraph-style finite-state logic.

---

## 🚀 Running the Backend

### 1. 🔐 Setup API Keys

Make sure you have access to the following:
- **Google AI Studio API key**
- **Firebase credentials (API key, project ID, etc.)**
- **Sarvam AI API key**
- Access to Google Cloud services:
  - Vertex AI for embeddings
  - Text-to-Speech
  - Language detection

You can optionally use **[ngrok](https://ngrok.com/)** to expose your local server for remote access.

### 2. 📦 Install Dependencies

```bash
cd backend
pip install -r requirements.txt
```
### 3. ▶️ Run Server

```bash
python server.py
```

### 💻 Running the Frontend

1. ⚙️ Requirements

    Node.js installed

    Svelte version 5 (install via npm)

2. 🚀 Start Dev Server

cd frontend
npm install
npm run dev

This will start the frontend on localhost:5173.```
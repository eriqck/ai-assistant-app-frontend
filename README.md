# 🤖 AI Assistant App

**AI Assistant App** is a simple, functional AI-powered question-answering tool built with a FastAPI backend and a static HTML/JavaScript frontend. It allows users to type any question and receive an intelligent response powered by OpenAI.

---

## 🧩 Project Structure

This project is divided into two main parts, both available on GitHub:

### 🔙 Backend (FastAPI)
- Built with **Python** using the **FastAPI** framework.
- Endpoint: `/ask` — accepts a question in JSON and returns an AI-generated answer.
- Uses **OpenAI's GPT model**.
- Deployed on **Render.com** as a web service.

🔗 Live API: [https://ai-assistant-backend-5tep.onrender.com/ask](https://ai-assistant-backend-5tep.onrender.com/ask)

### 🌐 Frontend (HTML + JavaScript)
- A lightweight single-page app using vanilla HTML, CSS, and JavaScript.
- Sends user input to the backend and displays the AI’s response.
- Deployed on **Render.com** as a static site.

🔗 Live App: [https://ai-assistant-app-frontend.onrender.com/](https://ai-assistant-app-frontend.onrender.com/)

---

## 📦 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, FastAPI, OpenAI API
- **Deployment**: Render.com

---

## 🚀 How It Works

1. User types a question into the web UI.
2. The frontend sends a `POST` request to the `/ask` endpoint on the backend.
3. The backend queries OpenAI's API and returns an AI-generated response.
4. The response is displayed on the page.

---

## 🧪 Example Use

**Question**:  
> What is the speed of light?

**Response**:  
> The speed of light in a vacuum is approximately 299,792 kilometers per second.

---

## 📁 Repository Structure



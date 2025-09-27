# Chatbot
# 🤖 Gemini Chatbot (LangGraph + FastAPI + Streamlit)

This project demonstrates how to build an **AI chatbot** using:
- [LangGraph](https://www.langchain.com/langgraph) for managing multi-turn conversations  
- [Google Generative AI (Gemini)](https://ai.google.dev/) as the LLM backend  
- [FastAPI](https://fastapi.tiangolo.com/) as the backend service  
- [Streamlit](https://streamlit.io/) as the frontend UI  
- [ngrok](https://ngrok.com/) to expose both services publicly from Google Colab  

---

## 🚀 Features
- Conversational chatbot powered by **Gemini 2.0 Flash Lite**  
- FastAPI backend that maintains a **chat history (`chat_history.json`)**  
- Streamlit frontend for interactive chatting  
- Option to **download chat history** from Colab  
- Runs fully inside **Google Colab** with public ngrok links  

---

## 📦 Installation
Run this in a Colab notebook cell to install dependencies:

```bash
!pip install -qU langchain_google_genai langgraph fastapi uvicorn nest-asyncio pyngrok streamlit requests

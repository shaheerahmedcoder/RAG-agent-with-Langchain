

# 📄 RAG Chatbot with LangChain

This project is a **Retrieval-Augmented Generation (RAG) chatbot** built using LangChain, OpenAI, FAISS, and Gradio. It allows you to upload a PDF and ask questions based on its content.

---

## 🚀 Features

* Upload any PDF document
* Split document into small chunks
* Convert text into embeddings
* Store and search using FAISS
* Ask questions and get AI-powered answers
* Chat interface using Gradio
* Maintains chat history (memory)

---

## 🛠️ Tech Stack

* Python
* LangChain
* OpenAI GPT-4o-mini
* FAISS (Vector Database)
* PyPDF
* Gradio

---

## ⚙️ How it Works

1. Upload a PDF
2. Text is split into chunks
3. Chunks are converted into embeddings
4. Stored in FAISS vector database
5. User asks a question
6. Relevant chunks are retrieved
7. GPT generates an answer using only that context

---

## ▶️ Run Project

```bash
pip install -r requirements.txt
python app.py
```

---

## 🔐 Environment Variables

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

---

## 📌 Notes

* Do not hardcode API keys
* Works best with text-based PDFs
* Requires stable internet for OpenAI API

---


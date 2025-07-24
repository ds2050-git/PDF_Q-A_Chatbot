# PDF Q&A Chatbot — Llama 3 + Groq + FAISS + Streamlit

A fully local document QA system that lets you ask questions from a PDF using natural language. Powered by Groq's Llama 3, FAISS for fast vector search, and Streamlit for the user interface.

## Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Use

1. **Create and put PDFs inside `data/` folder**

   Example:

   ```
   /data/LLM24aug.pdf
   ```

2. **Create a `.env` file** in the root folder and include:

   ```env
   GROQ_API_KEY=your_groq_api_key
   HF_TOKEN=your_huggingface_token
   ```

3. **Run the Streamlit App**

   ```bash
   streamlit run app.py
   ```

---

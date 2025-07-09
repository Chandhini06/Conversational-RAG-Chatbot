# Conversational-RAG-Chatbot

This project is an interactive **Conversational Retrieval-Augmented Generation (RAG) chatbot** that enables users to upload PDF documents and ask **context-aware questions**. The chatbot uses **Google's Gemma-2 9B IT** LLM, **Hugging Face Embeddings**, and **ChromaDB** to deliver accurate, grounded answers.

Built using **Streamlit**, the app offers a clean UI and real-time, memory-enabled conversations based on the uploaded content.

---

## 🚀 Features

- ✅ **PDF Upload & Parsing** via `PyPDFLoader`
- ✅ **Text Chunking & Embedding** using `Hugging Face Sentence Transformers`
- ✅ **Vector Store Integration** with `ChromaDB`
- ✅ **LLM Response Generation** powered by `Gemma-2 9B IT`
- ✅ **Context-Aware Conversational Memory**
- ✅ **Streamlit UI** for real-time interaction and chat history

---

## 🛠️ Tech Stack

| Component | Description |
|----------|-------------|
| **Frontend** | for interactive chatbot interface |
| **LLM** | `Gemma-2 9B IT` (via Groq) |
| **Embedding Model** | `sentence-transformers/all-MiniLM-L6-v2` or similar |
| **Vector Store** | ChromaDB for storing & retrieving document chunks |
| **Document Loader** | `PyPDFLoader` from LangChain for parsing PDF |
| **LangChain** | For chaining LLMs, vector stores, and memory logic  |

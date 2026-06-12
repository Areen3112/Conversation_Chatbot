# Conversational RAG Chatbot 💬🧠

An intelligent **Conversational Retrieval-Augmented Generation (RAG) Chatbot** built using **LangChain**, **Groq LLMs**, and **Hugging Face Embeddings**. The application maintains conversation history, retrieves relevant context from a vector database, and generates accurate, context-aware responses using modern RAG techniques.

## ✨ Features

* 🤖 AI-powered conversational chatbot with memory
* 🧠 Maintains **chat history** for context-aware interactions
* 🔍 Implements **Retrieval-Augmented Generation (RAG)**
* 📚 Uses **vector embeddings** for semantic search
* ⚡ Efficient document retrieval using **retrievers**
* 🚀 Fast inference with **Groq LLMs**
* 🤗 Embedding generation using **Hugging Face models**
* 🔗 Modular pipeline built with **LangChain**
* 🌐 Easy deployment and API integration support

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **Groq API**
* **Hugging Face Embeddings**
* **Vector Stores (FAISS/ChromaDB)**
* **Retrievers**
* **Conversational Retrieval Chains**
* **RAG (Retrieval-Augmented Generation)**
* **Python-dotenv**

## 🏗️ Architecture

```text
User Query
    ↓
Conversation History
    ↓
Hugging Face Embeddings
    ↓
Vector Database
    ↓
Retriever
    ↓
Relevant Context Retrieval
    ↓
Groq LLM
    ↓
Context-Aware Response
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Areen3112/Conversation_Chatbot.git
cd conversational-rag-chatbot
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**macOS/Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token
```

> **Important:** Never commit your `.env` file or API keys to GitHub.

## ▶️ Running the Application

Start the chatbot application:

```bash
python app.py
```

Follow the prompts to begin interacting with the chatbot.

## 🧩 Core Concepts Implemented

* **Conversational Memory** – Maintains previous interactions to provide coherent multi-turn conversations.
* **Retrieval-Augmented Generation (RAG)** – Enhances responses using external knowledge retrieval.
* **Vector Embeddings** – Converts text into semantic representations for similarity search.
* **Vector Stores** – Efficient storage and retrieval of embedded documents.
* **Retrievers** – Fetches the most relevant context based on user queries.
* **LLM Integration** – Uses Groq-hosted language models for response generation.

## 🎯 Learning Outcomes

This project demonstrates:

* Building context-aware conversational AI systems
* Implementing end-to-end RAG pipelines
* Working with embeddings and vector databases
* Integrating Groq and Hugging Face services with LangChain
* Managing conversation history in chatbot applications

## 🚀 Future Improvements

* Add support for document uploads (PDF, DOCX)
* Integrate streaming responses
* Develop a web interface using Streamlit or FastAPI
* Support multiple vector databases
* Implement source citation for retrieved documents

## 🤝 Contributing

Contributions and suggestions are welcome. Feel free to fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License.

---

**Built with ❤️ using LangChain, Groq, Hugging Face, and RAG techniques.**

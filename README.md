# 📘 Conversational RAG with PDF Uploads & Chat History

This project is a **Streamlit app** that lets you upload PDF documents and chat with their contents.  
It uses **LangChain** for retrieval-augmented generation (RAG), **HuggingFace embeddings** for vector search, **Chroma** as the vector store, and **Groq’s LLaMA models** for generating responses.  
The chatbot also maintains **chat history** to answer follow-up questions contextually.

---

## ✨ Features
- 📂 Upload one or multiple PDF files
- 🔎 Split & embed documents with **HuggingFace Sentence Transformers**
- 📚 Store & search documents using **ChromaDB**
- 🧠 Context-aware answers with **LangChain’s history-aware retriever**
- 🤖 Use **Groq’s LLaMA model** for fast, high-quality responses
- 💬 Maintains **chat memory** across turns
- 🎨 User-friendly **Streamlit interface**

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
# On Linux/Mac:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set up environment variables
Create a .env file in the root of the project and add your API keys:
```bash
HF_TOKEN=your_huggingface_token
```
⚠️ Make sure .env is in your .gitignore so it won’t be pushed to GitHub.

### 5. Run the app
```bash
streamlit run app.py
```

## 📖 Usage

### 1.Enter your GROQ API key in the Streamlit app.

### 2.Upload one or more PDF files.

### 3.Ask questions in natural language.

### 4.The assistant retrieves the most relevant chunks and responds using the Groq LLaMA model.

### 5.Chat history is preserved, so you can ask follow-up questions.


## 🛠️ Tech Stack

### Streamlit
 - Web UI

### LangChain
 - RAG pipeline & memory

### ChromaDB
 - Vector database

### HuggingFace Embeddings
 - SentenceTransformers

### Groq
 - LLaMA-based LLM inference

### PyPDFLoader
 - PDF parsing


## 📂 Project Structure
```bash
.
├── app.py              # Main Streamlit app
├── requirements.txt    # Dependencies
├── .env                # API keys (not committed to Git)
├── .gitignore
```

## 📝 Example

### Upload a research paper PDF

### Ask: "What is the main contribution of this paper?"

### Follow up: "Who are the authors?"

### The assistant will retrieve and answer from the PDF context with memory of previous questions.


## 🙌 Contributions and improvements are welcome!
```yaml

👉 Do you want me to also **add example screenshots** (like PDF upload UI and chat output) to the README so your repo looks more attractive on GitHub?

```

# Auto-Insurance-Chatbot
An end-to-end Retrieval-Augmented Generation (RAG) chatbot designed to answer auto insurance policy queries. Features automated multi-metric evaluation, chunk optimization, and a Streamlit UI.
## 🛠️ Tech Stack & Architecture

* **LLM API:** OpenAI (ChatOpenAI, OpenAIEmbeddings)
* **Orchestration & Memory:** LangChain, LlamaIndex
* **Vector Store:** FAISS (Optimized over local Chroma DB and Pinecone experiments)
* **Local LLM Testing:** Ollama (Mistral, Nomic-embed-text)
* **Evaluation Frameworks:** RAGAs, Ollama, SentenceTransformers
* **Frontend:** Streamlit
Exceptional retrieval Relevancy (0.93) and Context Precision (0.91). Lower Faithfulness (0.64) points to minor generation hallucinations, marking our next target for prompt optimization.

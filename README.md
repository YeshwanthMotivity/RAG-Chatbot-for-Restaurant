# RAG-Chatbot-for-Restaurant-Support
RAG-Restaurant-Chatbot
🧠 RAG-Restaurant-Chatbot
This project is a Retrieval-Augmented Generation (RAG) Chatbot that helps users get quick answers about a restaurant's services, menu, and policies. It uses semantic search and a language model to provide accurate, context-aware responses.

🚀 Features
Semantic search powered by FAISS and MiniLM embeddings
AI-powered conversational responses using DialoGPT-small
Handles restaurant FAQs, menu items, contact info, etc.
Lightweight and optimized for local execution
Easily customizable for other domains


🛠️ Tech Stack
SentenceTransformer (MiniLM-L6-v2) – for text embeddings
FAISS – for fast vector similarity search
DialoGPT-small – for generating responses
Python and Jupyter Notebook


📄 How It Works
Load static restaurant documents (menu, FAQs, etc.).
Generate embeddings with SentenceTransformer.
Store embeddings in FAISS for similarity search.
Retrieve top-matching docs for a given query.
Feed retrieved context + query into DialoGPT-small to get the final response.


📸 Architecture Diagram
![Building LLM application using RAG - by Sagar Gandhi](https://github.com/user-attachments/assets/ed66e623-e3d4-4d7f-8d90-971f29771dfe)

💻 How to Run
1. Clone the repository:
git clone https://github.com/YeshwanthMotivity/RAG-Chatbot-for-Restaurant-Support.git
2. Rum the notebook:
Open Rag_Chatbot.ipynb in Jupyter Notebook
Execute the cells step by step.
Follow step-by-step execution

📈 Future Scope
Deploy with Flask/FastAPI or Streamlit for web access
Add multi-turn conversation memory
Support dynamic document updates

📬 Contact
For questions, reach out at:
📧 yeshwanth.mudimala@motivitylabs.com

# 🧠 RAG-Chatbot-for-Restaurant-Support
A Retrieval-Augmented Generation (RAG) Chatbot for a restaurant is a project designed to help users get quick, accurate answers to questions about the restaurant's menu, services, and policies. It combines semantic search with a language model to provide context-aware responses, making it more intelligent than a traditional chatbot.

---

## 🚀 Features
1. Semantic Search: Utilizes embeddings and a vector index (FAISS) to find the most relevant information for a given query.
2. AI-Powered Responses: Generates conversational and context-aware answers using the DialoGPT-small model.
3. Handles FAQs: The chatbot is trained to handle common questions about the restaurant's menu, contact information, and operating hours.
4. Lightweight & Local: The entire system is optimized to run efficiently on a local machine.
5. Easily Customizable: The framework can be adapted for use in other domains by simply swapping out the source documents.
     
---

### 🛠️ Tech Stack
| Component          |       Tool / Library         |                                 Purpose                        |
| ------------------ | ---------------------------- | -------------------------------------------------------------- |
| **Embeddings**     | `SentenceTransformer`        | Creates semantic vectors from text.                            |
| **Vector Search**  | `FAISS`                      | Provides fast and efficient vector similarity search.          |
| **Language Model** | `DialoGPT-small`             | Generates conversational responses based on retrieved context. |
| **Development**    | `Python`, `Jupyter Notebook` | The core programming language and development environment.     |

---

## 📄 How It Works
1. Loads Documents: The chatbot first loads a set of static restaurant documents (e.g., menus, FAQs, policies).
2. Generates Embeddings: A sentence transformer model creates numerical embeddings for each document.
3. Stores in FAISS: These embeddings are stored in a FAISS index to enable fast and efficient similarity search.
4. Retrieves Context: When a user asks a question, the system retrieves the top-matching documents from the FAISS index.
5. Generates Response: The retrieved context and the user's query are fed into the DialoGPT-small model, which generates the final, human-readable response.
   
---

## 📸 Architecture Diagram
![Building LLM application using RAG - by Sagar Gandhi](https://github.com/user-attachments/assets/ed66e623-e3d4-4d7f-8d90-971f29771dfe)

---

## 💻 How to Run
1. Clone the repository:
git clone https://github.com/YeshwanthMotivity/RAG-Chatbot-for-Restaurant-Support.git

2. Launch the notebook:
Open Rag_Chatbot.ipynb in Jupyter Notebook
Execute the cells step by step.
Follow step-by-step execution

---

## 📈 Future Scope
1. Web Deployment: Deploy the chatbot as a web application using frameworks like Flask, FastAPI, or Streamlit.
2. Multi-Turn Conversations: Add a feature to remember previous interactions for more natural conversations.
3. Dynamic Updates: Implement support for automatically updating documents as new information becomes available.

---

## 📬 Contact
For any questions, feel free to reach out at:
Email 📧: yeshwanth.mudimala@motivitylabs.com

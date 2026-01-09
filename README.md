# RAG Chatbot for Restaurant 🍽️

A Retrieval-Augmented Generation (RAG) chatbot designed to assist restaurant customers with menu inquiries, reservations, and opening hours. This repository contains multiple implementations ranging from local LLMs to remote Gemini API integration and voice capabilities.

## 📂 Project Structure

```
RAG-Chatbot/
├── notebooks/          # Jupyter Notebooks containing the chatbot implementations
│   ├── Rag_Chatbot.ipynb   # Local LLM Implementation (DialoGPT)
│   ├── Ragchatbott.ipynb   # Advanced Implementation with Gemini API
│   └── RagVoiceBot.ipynb   # Voice-enabled Chatbot Demo
├── requirements.txt    # Python dependencies
└── README.md           # Project Documentation
```

## 🚀 Notebooks Comparison

| Notebook | Model | Key Features | UI Framework |
|----------|-------|--------------|--------------|
| **`Ragchatbott.ipynb`** | **Gemini 1.5 Flash** (Remote) | Intelligent, context-aware responses. Best for high-quality text chat. | **Advanced Gradio** (Custom CSS, Chat Bubbles) |
| **`RagVoiceBot.ipynb`** | Rule-Based (Demo) | **Voice Interaction** (Speech-to-Text & Text-to-Speech). Good for demonstrating audio features. | **Advanced Gradio** with Audio Components |
| **`Rag_Chatbot.ipynb`** | `microsoft/DialoGPT-small` (Local) | Fully offline, privacy-focused. Simpler responses compared to Gemini. | Basic Gradio Interface |

## 🛠️ Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook or Google Colab

### Installation
1.  Clone the repository:
    ```bash
    git clone https://github.com/Yeshwanth2124/RAG-Chatbot-for-Restaurant.git
    cd RAG-Chatbot-for-Restaurant
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Chatbots
Navigate to the `notebooks/` directory and open your desired notebook.

*   **For `Ragchatbott.ipynb` (Recommended):**
    *   You will need a Google Gemini API Key.
    *   Set it in your environment variable `GEMINI_API_KEY` or paste it securely when prompted (do not hardcode it).
    *   Run all cells to launch the Gradio interface.

*   **For `RagVoiceBot.ipynb`:**
    *   Ensure you have a microphone connected.
    *   Run the notebook to interacts via voice.


## 🤝 Contributions
Contributions are welcome!
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## Author

**Yeshwanth Goud**

*Data Scientist | Full Stack & ML Enthusiast*



[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)]([https://your-live-link.com)](https://manav8826-chatbot-langgraph-streamlit-frontend-wxl7es.streamlit.app/)



# 🤖 LangGraph Chatbot

A conversational **AI Chatbot** built with [LangGraph](https://www.langchain.com/langgraph), featuring:
- **LangGraph backend** for dialogue management.
- **Streamlit frontend** for an interactive chat UI.

---

## 📌 Features
- 🧩 Built with **LangGraph** for structured conversational flow.
- 🖥️ Frontend powered by **Streamlit**.
- 🔐 Secure environment variable management with `.env`.
- 🛠️ Modular — extend with APIs, tools, and RAG pipelines.

---

## 🚀 Getting Started


git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git](https://github.com/manav8826/ChatBot_LangGraph/tree/main)
cd YOUR_REPO

2. Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3. Install Dependencies
pip install -r requirements.txt

4. Setup Environment Variables

Create a .env file:

GOOGLE_GENAI_AI_API_KEY=your_api_key_here


(See .env.example for reference.)

5. Run the Backend
python langgraph_backend.py

6. Run the Frontend
streamlit run streamlit_frontend.py

📂 Project Structure
├── langgraph_backend.py   # Backend logic using LangGraph
├── streamlit_frontend.py  # Streamlit UI for chatbot
├── requirements.txt       # Python dependencies
├── .env.example           # Example environment file
├── .gitignore             # Ignore secrets & build files
└── README.md              # Project documentation

🛠️ Tech Stack

Python

LangGraph

Streamlit

GoggleGenAI API

📌 Future Improvements

Add conversation memory (database/Redis).

Deploy on Streamlit Cloud or Render.

Add support for multi-agent workflows.

📜 License

MIT License


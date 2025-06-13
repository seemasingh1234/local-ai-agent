Build Local AI Agents with Python This project demonstrates how to build and run local AI agents entirely on your machine using Python, Ollama, LangChain, and ChromaDB as the vector search database. Everything is open-source and free to use—no cloud APIs or subscriptions required.

🚀 Overview In this project, you'll:

Set up a Python environment for working with local LLMs.

Use Ollama to run large language models (like LLaMA or Mistral) locally.

Leverage LangChain to build a structured AI agent workflow.

Store and retrieve vector embeddings using ChromaDB.

Integrate all components into a functional, local AI assistant.

📁 Project Structure local-ai-agent/ ├── main.py # Entry point for the agent ├── requirements.txt # Python dependencies ├── docs/ # Optional documentation resources ├── vector_store/ # Vector database storage └── README.md # You're here! 🧰 Technologies Used 🧠 Ollama – Lightweight LLM runner (https://ollama.com/)

🔗 LangChain – Framework for AI agent workflows

🧬 ChromaDB – Local vector database for embedding storage and search

🐍 Python 3.10+ – Main programming language

📦 Installation & Setup Clone this repo git clone https://github.com/techwithtim/LocalAI cd LocalAI Set up a virtual environment

python -m venv venv source venv/bin/activate # On Windows: venv\Scripts\activate Install dependencies

pip install -r requirements.txt Install and run Ollama

Download: https://ollama.com/download

Start a model (e.g. llama3): ollama run llama3 Run the project

python main.py

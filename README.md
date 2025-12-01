# AI-Chatbot


Shipun AI Chatbot 🤖 | Python + Gradio | Jupyter Notebook

A simple yet powerful Rule-Based Chatbot built using Python, trained on 40 custom Q&A, and deployed with an interactive Gradio UI.
This project is fully implemented inside a Jupyter Notebook, making it beginner-friendly and easy to run anywhere.

🚀 Project Overview

Shipun AI Chatbot is a lightweight conversational AI chatbot built using:

Python

NLTK (for text preprocessing)

Gradio (for web UI)

40 manually trained Q&A pairs

This chatbot follows a matching-based approach to find the best response based on text similarity.
You can easily expand it by adding more training data.

📂 Project Structure
📁 Shipun-AI-Chatbot
│
├── Shipun_AI_Chatbot.ipynb     # Main Jupyter Notebook
├── README.md                   # Project Documentation
└── requirements.txt (optional) # Dependencies list

⚙️ Features

✔️ 40+ Pre-trained Q&A
✔️ Simple and clean NLP pipeline (tokenization + lemmatization)
✔️ Rule-based matching
✔️ Fully interactive Gradio UI
✔️ Works offline
✔️ Beginner-friendly and customizable

🛠️ Technologies Used
Tool / Library	Purpose
Python	Core logic
NLTK	Text preprocessing
Gradio	Web-based UI
Jupyter Notebook	Development environment
📦 Installation
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/Shipun-AI-Chatbot.git
cd Shipun-AI-Chatbot

2. Install dependencies
pip install -r requirements.txt


Or manually install:

pip install gradio nltk

3. Start Jupyter Notebook
jupyter notebook


Open the file Shipun_AI_Chatbot.ipynb.

🧠 Training Data (40 Q&A)

The chatbot uses a simple JSON-like Python list containing 40 manually curated Q&A pairs such as:

“What is Python?”

“What is machine learning?”

“Tell me a joke”

“Who created you?”

“What is data science?”

You can customize or extend this list anytime.

▶️ How to Run the Chatbot

Inside the notebook:

Run the chatbot in console
You: Hello
Bot: Hi there! How can I help you?

Launch Gradio UI

The notebook contains:

iface.launch()


This opens your chatbot in browser:

🌐 http://127.0.0.1:7860/

🖥️ Gradio User Interface

The UI contains:

A text box for user input

A clean output text area

Custom title and description:
“Shipun AI Chatbot – Trained on 40 Q&A”

📈 Future Enhancements

You can extend this project by adding:

🔹 TF-IDF semantic similarity
🔹 Sentence-BERT embeddings
🔹 Chat history support
🔹 API deployment (FastAPI / Flask)
🔹 Streamlit UI
🔹 Database storage for Q&A
🔹 Voice input/output

🤝 Contributing

Contributions are welcome!
You can:

Add new Q&A pairs

Improve NLP model

Add new features

Improve UI

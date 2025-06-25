# Career Chatbot

This is an AI-powered career chatbot built with **Streamlit** and **LangChain** that helps users interactively explore career paths, analyze documents, and get insights from uploaded files.

## 🚀 Features

- **Career Guidance Chatbot**: Ask questions related to career paths, skills, and job preparation.
- **Document Processing**: Upload and process PDF, DOCX, PPTX, and email files for insights.
- **LLM Integration**: Uses LangChain + Google Generative AI for natural language interaction.
- **Search & Summarization**: Search across documents and generate summaries.
- **Streamlit UI**: Simple, interactive web app interface.

---

## 🛠 Installation

1️⃣ **Clone the repository**
```bash
git clone https://github.com/deepshikasaravanan/Career-chatbot.git
cd Career-chatbot

2️⃣ Create and activate a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Set environment variables

bash
Copy
Edit
cp env.example .env
Edit .env and add your API keys (e.g., Google Generative AI key).

▶️ Usage
Run the app:

bash
Copy
Edit
streamlit run app.py
Open in your browser at http://localhost:8501/.

📂 Project Structure
bash
Copy
Edit
├── app.py               # Streamlit app main file
├── requirements.txt      # Python dependencies
├── env.example           # Example env file (update as .env)
└── README.md             # This file
⚙ Dependencies
Key packages:

streamlit

langchain

google-generativeai

pandas, numpy

beautifulsoup4, pdfminer.six, docx2txt, python-pptx

faiss-cpu for vector search

(See requirements.txt for full list)

📌 Notes
✅ Python 3.9+ recommended
✅ Ensure valid API keys in .env
✅ Tested locally on macOS


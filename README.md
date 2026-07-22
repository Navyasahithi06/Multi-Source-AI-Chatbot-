# Multi-Source-AI-Chatbot
Here's a more professional, modern, and GitHub-friendly version of your README.

---

# 🤖 Multi-Source AI Chatbot

An AI-powered web application that combines multiple intelligent services into a single platform. Users can interact with an AI assistant, summarize PDF documents, extract insights from YouTube videos, and generate images from text prompts through a simple and intuitive interface.

---

# 📖 About the Project

The **Multi-Source AI Chatbot** is a Streamlit-based application designed to bring multiple AI capabilities together in one place. Rather than using separate tools for chatting, document analysis, video summarization, and image generation, this application provides a unified experience powered by Large Language Models (LLMs).

The chatbot processes different types of user inputs, generates context-aware responses, and stores conversation history securely, making it suitable for students, researchers, and professionals.

---

# ✨ Key Features

* 🤖 Intelligent AI conversational assistant
* 📄 Automatic PDF document summarization
* 🎥 YouTube video transcript summarization
* 🖼️ AI-powered image generation from text prompts
* 👤 User authentication with Login and Signup
* 💾 SQLite database for storing user and chat history
* 🌐 Interactive Streamlit web interface
* 🔑 Secure API key management using environment variables
* ⚡ Fast and responsive user experience
* 🛡️ Robust error handling for invalid documents, unavailable transcripts, and API failures

---

# 🏗️ System Architecture

```text
                    User
                      │
                      ▼
             Streamlit Web Interface
                      │
     ┌────────────┬──────────────┬──────────────┐
     │            │              │              │
     ▼            ▼              ▼              ▼
 AI Chat      PDF Summary   YouTube Summary   Image Generation
     │            │              │              │
     └────────────┴──────────────┴──────────────┘
                      │
              AI Models & APIs
                      │
          Chat History (SQLite Database)
```

---

# 🛠️ Technology Stack

### Frontend

* Streamlit

### Backend

* Python

### AI Services

* Groq API (Large Language Model)
* Hugging Face API (Image Generation)

### Database

* SQLite

### Libraries

* LangChain
* PyPDF2
* youtube-transcript-api
* python-dotenv
* Pillow
* Requests

---

# 📂 Project Structure

```text
MULTI_SOURCE_AI_CHATBOT/
│
├── app.py
├── auth.py
├── users.py
├── utils.py
├── database.db
├── requirements.txt
├── .env
├── generated_images/
├── outputs/
├── fonts/
└── README.md
```

---

# ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/MULTI_SOURCE_AI_CHATBOT.git
cd MULTI_SOURCE_AI_CHATBOT
```

### Create a Virtual Environment

```bash
python -m venv .venv
```

### Activate the Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### Install Required Packages

```bash
pip install -r requirements.txt
```

---

# 🔐 Configure Environment Variables

Create a **.env** file in the project directory.

```env
GROQ_API_KEY=your_groq_api_key
HF_API_KEY=your_huggingface_api_key
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and navigate to:

```
http://localhost:8501
```

---

# 🚀 Application Workflow

```text
User Login
     │
     ▼
Choose a Feature
     │
 ┌───┼───────────────┬──────────────┬──────────────┐
 │   │               │              │              │
 ▼   ▼               ▼              ▼
Chat PDF Summary YouTube Summary Image Generation
 │   │               │              │
 └───┴───────────────┴──────────────┘
           │
     AI Processing
           │
           ▼
   Display Results
           │
           ▼
 Save Chat History in SQLite
```

---

# 📸 Application Modules

### 🔑 User Authentication

Secure Login and Signup system for managing user accounts.

### 💬 AI Chat

Interact with an intelligent AI assistant capable of answering user queries in real time.

### 📄 PDF Summarization

Upload PDF documents and receive concise summaries generated using AI.

### 🎥 YouTube Video Summarization

Provide a YouTube video link to generate a summary from its transcript.

### 🖼️ AI Image Generation

Generate creative images by entering descriptive text prompts.

---

# 🎯 Learning Outcomes

* Building AI-powered applications with Python
* Integrating Large Language Models (LLMs)
* Document processing and summarization
* YouTube transcript extraction
* AI image generation
* User authentication and database management
* Streamlit application development
* API integration and secure key management

---

# 🔮 Future Enhancements

* Support for multiple document formats (Word, PPT, TXT)
* Voice-based chatbot interaction
* Multi-language support
* Conversation export to PDF
* Cloud database integration
* Chat session management
* Deployment on Streamlit Cloud or AWS
* Advanced prompt customization

---

# 👩‍💻 Author

**M. Navya Sahithi**

B.Tech – Artificial Intelligence & Data Science

Aspiring Data Analyst | AI & Machine Learning Enthusiast

---

# 📜 License

This project is developed for educational and learning purposes. It is open for modification, experimentation, and academic use.

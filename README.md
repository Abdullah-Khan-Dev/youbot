# Youbot 🎥🤖  
**No time to watch? Link it. Done.**  

Youbot is an AI-powered application that lets you **chat with YouTube videos**.  
Instead of spending hours watching, simply paste a link and instantly:  
- Summarize the video  
- Ask questions about any part of it  
- Get detailed explanations (perfect for studying & research)  

It’s fast, efficient, and capable of handling even **10+ hour-long YouTube videos within seconds**.  

---

## ✨ Features  
- 📌 **Summarization** – Get concise summaries of long videos  
- 🔍 **Q&A** – Ask specific questions and receive contextual answers  
- 📚 **Explanations** – Break down complex concepts for better understanding  
- ⚡ **Speed** – Parallel processing enables lightning-fast results, even on very long videos  
- 🎨 **Modern UI** – Clean React-based frontend designed in Figma  

---

## 🛠️ Tech Stack  
- **Frontend:** React (Vite) · Figma (UI/UX Design)  
- **Backend:** FastAPI  
- **AI/ML:** LangChain (RAG system with custom runnables & parallel chains)  
- **Transcription:** YouTube Transcript Loader  

---

## 🚀 How It Works  
1. Paste a YouTube link into Youbot  
2. The system fetches and transcribes the video  
3. Transcripts are processed through a **custom Retrieval-Augmented Generation (RAG) pipeline**  
4. Ask questions, get summaries, or request explanations instantly  

---

## 📂 Project Structure  
```bash
youbot/
├── frontend/   # React (Vite) frontend
├── backend/    # FastAPI backend with LangChain RAG pipeline
├── README.md   # Project documentation
└── LICENSE     # Open-source license
````

---

## 🖥️ Setup & Installation

### Clone the Repository

```bash
git clone https://github.com/Abdullah-Khan-Dev/youbot.git
cd youbot
```

### Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

### Backend (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 🌟 Motivation

The idea behind Youbot is simple:
⏳ **Time is money.** Why waste hours watching videos when you can extract insights in seconds?

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a PR.

---

## 🙌 Acknowledgements

* [LangChain](https://www.langchain.com/)
* [FastAPI](https://fastapi.tiangolo.com/)
* [React](https://react.dev/)

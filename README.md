An app that requires a youtube url to generate notes/summary and a chatbot to discuss any doubts regarding the video.


**Streamlit Link:** [https://parth-rag-yt.streamlit.app/](https://parth-rag-yt.streamlit.app/)

# 🎥 YouTube RAG Synthesizer

An AI-powered Streamlit application that transforms any YouTube video into **concise notes** or an **interactive chatbot** experience using Retrieval-Augmented Generation (RAG) with Gemini LLM.

---

## 🚀 Features

- 🎬 **YouTube Transcript Fetching** – Automatically extracts subtitles using `yt-dlp`, avoiding API rate limits.  
- 🌐 **Multi-Language Support** – Detects and translates non-English transcripts into English using Gemini.  
- 🧠 **RAG-based Chatbot** – Chat directly with any video using vector embeddings (HuggingFace + Chroma).  
- 📝 **Smart Note Generation** – Generates structured, bulleted notes and highlights key topics from the video.  
- ⚡ **Streamlit UI** – Intuitive and minimal interface for quick interaction and analysis.  

---

## 🧩 Tech Stack

- **Frontend:** Streamlit  
- **LLM:** Google Gemini (via `langchain-google-genai`)  
- **Vector Database:** Chroma  
- **Embeddings:** HuggingFace (`all-MiniLM-L6-v2`)  
- **Transcript Extraction:** yt-dlp  
- **Language Translation & Notes:** Gemini model (Gemini 2.5 Flash Lite)  
- **Backend:** Python  

---

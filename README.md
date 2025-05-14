# YouTube-RAG-Chatbot-
A Retrieval-Augmented Generation (RAG) based chatbot that can answer questions from any YouTube video using its transcript.

# What It Does
Given a YouTube video ID, the chatbot:
1. Fetches the video transcript using the YouTube Transcript API.
2. Splits the transcript into manageable chunks.
3. Converts those chunks into vector embeddings using OpenAI's models.
4. Stores them in a FAISS vector store for fast retrieval.
5. Uses LangChain's RetrievalQA to generate answers to user queries about the video.

# Tech Stack
- 🦜 LangChain
- 🔮 OpenAI API (for embeddings and language model)
- 🧠 FAISS (Vector DB)
- 📼 YouTube Transcript API
- 🧮 Tiktoken (for token-aware chunking)
- 🐍 Python

# TODOs & Improvements
- Add Streamlit web interface
- Support multiple video queries
- Add transcript caching for performance
- Add Docker support

# License
MIT License. Feel free to use and modify!

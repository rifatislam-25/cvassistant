🚀 AI-Powered CV Assistant
An interactive chatbot designed to answer questions about your CV using LangChain, FAISS, and Groq API. It leverages semantic search and conversational memory to deliver accurate and context-aware responses.

🛠️ Features
✔ Conversational AI – Uses Groq API (Llama 3.1-8B) for generating human-like responses.
✔ FAISS-based Retrieval – Converts CV text into vector embeddings for fast and efficient search.
✔ Memory – Maintains context-awareness by remembering previous conversations.
✔ Streamlit UI – Provides an intuitive chat interface for user interaction.
✔ Secure API Handling – Loads GROQ_API_KEY securely from environment variables or Streamlit secrets.
✔ Deployment Ready – Can be hosted on Streamlit & GitHub for easy access.

📌 How It Works
1️⃣ Text Preprocessing:

The CV text is split into small chunks to improve retrieval accuracy.
2️⃣ Vector Storage:

These text chunks are converted into vector embeddings using sentence-transformers.
The embeddings are stored in FAISS (Facebook AI Similarity Search) for fast retrieval.
3️⃣ Retrieval + Chat:

When a user asks a question, FAISS searches for the most relevant chunks of text.
The Groq API (Llama 3.1-8B) generates a response based on the retrieved information.
4️⃣ Conversational Memory:

The chatbot uses LangChain's memory module to remember previous interactions.
This enables context-aware conversations, making responses more coherent over time.
This AI-Powered CV Assistant ensures a seamless and intelligent interaction for answering CV-related queries efficiently. 🚀






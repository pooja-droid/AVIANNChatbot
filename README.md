# 🐦 Aviann — Retrieval-Based Bird Chatbot

Aviann is a retrieval-based chatbot built in Python that answers user questions about birds.  
It retrieves the most relevant response from a curated dataset using Natural Language Processing (NLP) techniques such as TF-IDF, Bag-of-Words, and cosine similarity.

---

## How It Works

1. The user asks a question about birds (e.g., *“What do owls eat?”*).
2. The chatbot processes the input using:
   - Tokenisation & lemmatisation
   - TF-IDF vectorisation
3. The chatbot extracts intent and entities from the user message.
3. Cosine similarity is used to compare the question with stored knowledge.
4. AVIANN returns the most relevant match from the dataset.

---

## Tech Stack

| Component         | Technologies Used     |
|------------------|------------------------|
| Language         | Python                 |
| NLP Libraries    | NLTK, scikit-learn     |
| Algorithms       | TF-IDF, Bag-of-Words, Cosine Similarity |
| Data             | Custom bird knowledge base (text) |
| Interface        | Command-line |

---

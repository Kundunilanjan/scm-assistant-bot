# SCM Assistant Bot

## Project Overview

This project is a Retrieval-Augmented Generation (RAG) chatbot built using Flowise Cloud.  
The chatbot uses uploaded documents as a knowledge base and answers user questions using an LLM integrated with a vector database and embeddings model.

---

# Public Chatbot URL

Add your deployed chatbot URL here:

```text
https://your-chatbot-url](https://cloud.flowiseai.com/chatbot/ba9bef9c-97ea-405c-9e22-cb39cb86fa4d
```

---

# GitHub Repository

Add your GitHub repository link here:

```text
https://github.com/Kundunilanjan/scm-assistant-bot
```

---

# Technologies Used

## Flowise Platform
- Flowise Cloud

## LLM Used
Example:
- Groq Llama 3 70B
or
- Gemini 1.5 Flash

## Embedding Model Used
- sentence-transformers/all-MiniLM-L6-v2

## Vector Database
- ChromaDB

## Text Splitter
- Recursive Character Text Splitter

---

# Document Store Configuration

## Chunk Configuration 1

| Parameter | Value |
|---|---|
| Chunk Size | 500 |
| Chunk Overlap | 50 |

### Chunk Count Results

| File Name | Chunk Count |
|---|---|
| File 1 | Add Count |
| File 2 | Add Count |

---

## Chunk Configuration 2

| Parameter | Value |
|---|---|
| Chunk Size | 1000 |
| Chunk Overlap | 100 |

### Chunk Count Results

| File Name | Chunk Count |
|---|---|
| File 1 | Add Count |
| File 2 | Add Count |

---

# Chatflow Architecture

```text
Chat Input
   ↓
Conversational Retrieval QA Chain
   ↓
Document Store Retriever
   ↓
LLM
   ↓
Chat Output
```

---

# Questions and Answers

## Question 1

### Question
```text
Add Question 1 Here
```

### Answer
```text
Paste chatbot answer verbatim here
```

---

## Question 2

### Question
```text
Add Question 2 Here
```

### Answer
```text
Paste chatbot answer verbatim here
```

---

## Question 3

### Question
```text
Add Question 3 Here
```

### Answer
```text
Paste chatbot answer verbatim here
```

---

## Question 4

### Question
```text
Add Question 4 Here
```

### Answer
```text
Paste chatbot answer verbatim here
```

---

## Question 5

### Question
```text
Add Question 5 Here
```

### Answer
```text
Paste chatbot answer verbatim here
```

---

# Screenshots Included

The `/screenshots` folder contains:

- Flowise dashboard
- Document upload
- Chunk configuration 1
- Chunk configuration 2
- Embeddings setup
- Vector database setup
- LLM configuration
- Chatflow pipeline
- Chatbot testing
- Public deployment

---

# Files Included

```text
scm-assistant-bot/
├── scm_assistant.json
├── README.md
├── .gitignore
└── screenshots/
```

---

# Improvements I Would Make

If given more time, I would improve the project by:

- Adding memory for conversational context
- Using hybrid search retrieval
- Adding reranking models
- Improving UI/UX
- Adding authentication
- Using larger embedding models
- Optimizing chunking strategy
- Adding citation-based answers
- Deploying with custom frontend integration

---

# Notes

- API keys and `.env` files are excluded using `.gitignore`
- The repository is public as required
- The chatbot was tested successfully using all provided questions

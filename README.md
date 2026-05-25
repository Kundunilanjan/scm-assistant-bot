<img width="2862" height="1781" alt="chatflow_architecture" src="https://github.com/user-attachments/assets/1d19bc09-5b2a-4cb1-a278-e61653b97e77" /># SCM Assistant Bot

## Project Overview

This project is a Retrieval-Augmented Generation (RAG) chatbot built using Flowise Cloud.  
The chatbot uses uploaded documents as a knowledge base and answers user questions using an LLM integrated with a vector database and embeddings model.

---

# Public Chatbot URL

Add your deployed chatbot URL here:

```text
https://cloud.flowiseai.com/chatbot/ba9bef9c-97ea-405c-9e22-cb39cb86fa4d
```

---

# GitHub Repository

Add your GitHub repository link here:

```text
https://github.com/Kundunilanjan/scm-assistant-bot
```

---

# Technologies Used in Chatflow

## Flowise Platform
- Flowise Cloud

## LLM Model Used
- Groq LLM
- Model: Llama 3 70B

## Embedding Model Used
- HuggingFace Embeddings
- Model: sentence-transformers/all-MiniLM-L6-v2

## Vector Database
- LangChain In-Memory Vector Store
- Used for temporary vector embeddings and retrieval during chatbot execution

## Text Splitter
- Recursive Character Text Splitter

---

# Document Store Configuration

## Chunk Configuration

| Parameter | Value |
|---|---|
| Chunk Size | 1000 |
| Chunk Overlap | 100 |

### Chunk Count Results

| File Name | Chunk Count |
|---|---|
| supplier_performance_data | 2000 |
| SupplyChain_Governance_Policy_v3.2 1 | 19 |

---

# Chatflow Architecture

<img width="2862" height="1781" alt="chatflow_architecture" src="https://github.com/user-attachments/assets/e2c84688-6ff0-4e01-b2cb-2accf8abc134" />



---

# Questions and Answers

## Question 1 Screenshot

<img width="1202" height="870" alt="q1_question-answer-screenshot" src="https://github.com/user-attachments/assets/78fcbdcf-efda-44e5-b64f-69e30865564d" />



---

## Question 2 Screenshot

<img width="1130" height="754" alt="q2_question-answer" src="https://github.com/user-attachments/assets/419070dc-9db0-40a2-a134-145d76d81a3e" />
<img width="1112" height="763" alt="Screenshot 2026-05-25 053726" src="https://github.com/user-attachments/assets/77b5519f-812d-408f-a949-878c7e85a651" />



---

## Question 3 Screenshot

<img width="1113" height="329" alt="q3_question-answer-screenshot" src="https://github.com/user-attachments/assets/be009878-e9fd-4079-848c-10e649435b74" />


---

## Question 4 Screenshot

<img width="1127" height="685" alt="q4_question-answer" src="https://github.com/user-attachments/assets/151bf070-7f69-477e-8cff-4efac5c99855" />


---

## Question 5 Screenshot

<img width="1115" height="362" alt="q5_question-answer" src="https://github.com/user-attachments/assets/c1dfe61a-6d6e-411a-94e8-0ccbe98b4d4a" />


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

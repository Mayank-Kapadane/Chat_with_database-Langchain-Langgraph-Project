# Chat With Database using AI

## What is this Project?

This project lets users interact with a database using natural language instead of writing SQL queries. The AI understands the question, retrieves the required information from the database, and returns a meaningful answer.

---

## How It Works

### Scenario 1 – Intelligent Table Selection

Uses vector search on database schema and table descriptions to identify the most relevant tables before generating SQL queries.

### Scenario 2 – Semantic Data Search

Uses embeddings and vector search to find information from the actual database content based on meaning rather than exact keywords.

### Fusion Approach

Combines Scenario 1 and Scenario 2 to leverage both structured SQL querying and semantic search for more accurate and context-aware responses.

---

## Technologies Used

* Python
* SQLite
* LangChain
* OpenAI Embeddings
* FAISS Vector Database
* SQL Database

---

## Features

* Query databases using natural language
* Automatic SQL query generation
* Intelligent table selection using vector search
* Semantic search on database records
* Hybrid retrieval using SQL and embeddings
* Context-aware response generation
* AI-powered database assistant

---

## Project Architecture

1. User asks a question in natural language.
2. The system analyzes the query.
3. Relevant tables are identified using vector search (Scenario 1).
4. Relevant data is retrieved using semantic search when required (Scenario 2).
5. The Fusion layer combines results from both approaches.
6. AI generates a clear and meaningful response.

---

## Project Goal

To simplify database interaction by allowing users to ask questions in plain English while combining the power of SQL databases and AI-based semantic search.

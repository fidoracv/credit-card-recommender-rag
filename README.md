**Credit Card Recommendation Chatbot**
An AI-powered chatbot that recommends credit cards based on customer profiles using Retrieval-Augmented Generation (RAG) and agentic AI patterns.

**Code Process:**
A customer enters their profile (income, spending habits, reward preferences) and the AI:
Analyzes their needs
Searches a RAG knowledge base for relevant card information
Recommends the best-fit credit card with personalized reasoning
Provides direct application link and calendar reminder for follow-up

Example:
**Input: Output**
Online shopper, S$50K income, wants cashback → DBS Live Fresh Card (5% cashback on online)
Frequent traveler, S$80K income, wants miles → DBS Altitude Card (3 miles per $1 overseas)
Car owner, high petrol spending → DBS Esso Card (21.8% petrol savings)
Family, grocery shopping → DBS yuu Card (10 points per $1 at Cold Storage/Giant)

**Tech Stack**
Component : Technology
LLM: Ollama (Llama 3.2)
Framework: LangChain
Vector DB: ChromaDB
Frontend: Gradio
Language: Python

**Architecture**
User Profile → Rule-Based Matching → RAG Retrieval → LLM Explanation → Recommendation
↓                    ↓                ↓
(Card Selection)     (ChromaDB)      (Ollama/Llama)
Agentic AI Development — Multi-step reasoning pipeline
RAG Implementation — Vector search with ChromaDB + LangChain
Prompt Engineering — Structured prompts for reliable outputs
Python Development — Clean, modular code structure
UI/UX — Interactive web interface with Gradio
Problem Solving — Hybrid rule-based + LLM approach to ensure consistency

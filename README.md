# LangGraph-TreeOfThought-RAG-
Multi-agent LangGraph project using Tree of Thought prompting and ChromaDB for RAG.

## Overview
Lightweight, crash-proof implementation of a RAG pipeline enhanced with Tree-of-Thought reasoning and a multi-agent design:
- Chunking strategies (Fixed-size sliding + Semantic)
- Retriever Agent (light in-memory TF vectors + cosine similarity)
- Query Planner Agent (vector vs web decision logic)
- Synthesizer, Writer & Reviewer Agents
- Tree-of-Thought (ToT) reasoning demo
- RAGAS-like evaluation metrics (demo)

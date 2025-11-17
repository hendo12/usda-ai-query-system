# USDA AI Query System

**Status:** Proof-of-Concept / Personal R&D

## 1. The Problem
USDA insurance policy documents are dense, complex, and hundreds of pages long. For insurance agents or farmers needing a quick, specific answer, manually searching these documents is time-consuming and inefficient. This can lead to delays in decision-making and a high risk of misinterpreting complex regulations.

## 2. The Solution
This project is an AI-driven RAG (Retrieval-Augmented Generation) system designed to streamline USDA insurance policy lookups. It allows a user to ask a natural language question (e.g., "What are the reporting requirements for prevented planting?") and receive a precise, cited answer directly from the source documents.

The goal was to create a proof-of-concept for an AgTech-specific AI workflow that could dramatically reduce research time and improve the accuracy of information retrieval for agricultural professionals.

## 3. Key Features & Technical Highlights
*   **RAG Pipeline:** Implemented a full Retrieval-Augmented Generation pipeline to ingest and index the dense policy documents.
*   **Conversational Interface:** The system is designed to be used through a simple, conversational query interface, making it accessible to non-technical users.
*   **Accurate, Cited Responses:** The AI workflow is engineered to provide answers directly supported by the text and to cite the source document and page number, ensuring verifiability and trust.

## 4. Tech Stack
*   **Language:** Python
*   **AI/ML Framework:** LangChain
*   **Vector Database:** ChromaDB
*   **LLM & Embeddings:** OpenAI API

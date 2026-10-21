# Document-Vector-RAG

## Overview
This repository contains a Retrieval-Augmented Generation (RAG) workflow built with [Langflow](https://github.com/logspace-ai/langflow). It allows users to upload PDF documents (like train tickets, invoices, or technical specs) and query them using natural language to extract precise, context-aware answers.

## Features
* **Built-in Vector Store**: Uses Langflow's native Chroma Local DB for seamless, configuration-free document embedding.
* **Fast & Reliable LLM**: Integrated with Google's `gemini-3.5-flash-lite` for high-speed, low-latency inference, bypassing high-demand server bottlenecks.
* **Visual Node Architecture**: Fully visual pipeline setup, making it easy to debug, modify, and scale for custom AI workflows.

## Tech Stack
* Langflow (v1.x)
* Google Generative AI (Gemini API)
* ChromaDB (Local)
* Python 3.12+

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/yourusername/Langflow-RAG-Bot.git](https://github.com/yourusername/Langflow-RAG-Bot.git)
   cd Langflow-RAG-Bot

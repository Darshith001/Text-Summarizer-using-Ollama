# Text-Summarizer-using-Ollama

This project is a web content summarizer powered by Ollama (local LLM runner).
It allows users to input a URL, extract the page text, and generate a clear, concise summary.
The goal is simple: Read long articles, blogs, or documentation and get an instant, meaningful summary.

Features

🔗 URL to Text Extraction – Automatically fetch and clean website content

🧩 Local AI Summarization using Ollama (supports Llama, Mistral, Phi, etc.)

🛠 Custom System & User Prompts

⚡ Fast, offline, privacy-friendly

Technology Stack

AI Engine: Ollama (local LLM models)
Models Supported: llama3, mistral, phi3, etc.
Libraries:BeautifulSoup 
Ollama API for model inference

💡 How It Works

*User enters a website URL
*The system fetches and cleans the HTML
*Text is chunked and sent to the Ollama model
*A system prompt controls the behavior (e.g., “You are a summarizer AI…”)
*A user prompt refines how the summary should look
*The model returns a clean, structured summary

# Local Command-Line Chatbot

## Overview
This project is a local command-line chatbot built with Hugging Face’s Transformers library.  
It runs fully offline, uses a small text generation model (`distilgpt2` by default), and maintains a short conversation memory using a sliding window buffer.  

The chatbot was developed as part of the **ATG Technical Assignment**.

---

## Features
- Runs locally (no API required)
- Built with Python & Hugging Face Transformers
- Maintains conversational memory (last 3 turns)
- Modular structure (`model_loader.py`, `chat_memory.py`, `interface.py`)
- CLI interface with `/exit` to quit
- Jupyter Notebook version for quick testing

---

## Installation

1. Clone the repository or extract the provided zip:
   ```bash
   git clone <repo-link>
   cd chatbot

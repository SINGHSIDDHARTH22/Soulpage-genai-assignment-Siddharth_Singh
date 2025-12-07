# Conversational AI Agent (Task 2)

This project implements a context-aware chatbot using **LangGraph** and **Llama 3.1**. It features persistent memory and intelligent tool usage, utilizing web search only when necessary for current events or external facts.

## Prerequisites

1.  **Python 3.10+**
2.  **Ollama**: Ensure Ollama is installed. [Download here](https://ollama.com).

## Setup Instructions

1.  **Install Python Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2.  **Prepare the Model:**
    Open a terminal and run the following commands to start the server and download the required model:
    ```bash
    ollama serve
    # In a new terminal window:
    ollama pull llama3.1
    ```

## How to Run

Execute the main script:
```bash
python chatbot.py

# GenAi-LangChain
# GenAI with LangChain

A beginner-friendly Generative AI project built using Python, LangChain, and Groq. This project focuses on learning how to build AI applications using Large Language Models and LangChain.

## Features

- Integration with Large Language Models
- LangChain-based AI applications
- Groq API integration
- Environment variable support for API keys
- Beginner-friendly project structure

## Technologies Used

- Python
- LangChain
- Groq
- uv
- Git
- GitHub

## Project Structure

```text
GenAi/
│
├── .gitignore
├── README.md
├── pyproject.toml
├── uv.lock
└── ...
```

## Installation

Clone the repository:

```bash
git clone https://github.com/panday-mahima-panday/GenAi-LangChain.git
```

Go to the project directory:

```bash
cd GenAi-LangChain
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

If you are using uv:

```bash
uv sync
```

## API Key Setup

Create a `.env` file in the project root directory:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Never upload your `.env` file or API keys to GitHub.

Add the following to `.gitignore`:

```gitignore
.env
.venv/
__pycache__/
*.pyc
```

## Run the Project

After activating the virtual environment, run the required Python file:

```bash
python main.py
```

Replace `main.py` with the appropriate file name if your project uses a different entry point.

## Learning Goals

This project is created to learn and practice:

- Generative AI
- Large Language Models
- LangChain
- Prompt Engineering
- API Integration
- Python Virtual Environments
- Git and GitHub

## Future Improvements

- Build a chatbot
- Explore Retrieval-Augmented Generation (RAG)
- Add document-based question answering
- Explore Lang

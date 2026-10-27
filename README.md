# AI-Personal-Assistant-
A Python-based AI assistant using the OpenAI API for query answering, email summarization, image generation, and image editing.

# AI Personal Assistant 🤖

## Overview

AI Personal Assistant is a Python-based project built using the OpenAI API. It demonstrates how AI can be used to answer user queries, summarize emails, generate images, and edit images using text prompts.

## Features

- **Query Answering:** Get AI-generated responses to user questions.
- **Email Summarization:** Summarize email content into 2–3 sentences.
- **Image Generation:** Generate images from text prompts.
- **Image Editing:** Edit an existing image using text instructions.

## Technologies Used

- Python
- OpenAI API
- Base64 for decoding generated image data

## Project Structure

```text
AI-Personal-Assistant/
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Prerequisites

- Python installed on your system
- An OpenAI API key
- Internet connection

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/lalitkumar180503/AI-Personal-Assistant.git
cd AI-Personal-Assistant
```

**2. Create a virtual environment (recommended)**

```bash
python -m venv .venv
```

On Windows PowerShell, activate it using:

```powershell
.venv\Scripts\Activate.ps1
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

## API Configuration

Set your OpenAI API key using an environment variable named `OPENAI_API_KEY`.

Never commit your API key or other secrets to GitHub.

## Run the Project

If your main Python file is named `main.py`, run:

```bash
python main.py
```

Follow the prompts displayed in the terminal.

## How It Works

1. The user provides a question, email, or image-related instruction.
2. The application sends the relevant request to the OpenAI API.
3. The API returns a response or generated image data.
4. The application displays the response or saves the image locally.

## Future Improvements

- Add a menu-driven interface for selecting assistant features.
- Improve error handling and input validation.
- Add conversation history.
- Make the application easier to use through a graphical interface.

## Author

**Lalit Kumar Saraswat**

GitHub: [lalitkumar180503](https://github.com/lalitkumar180503)

---

*This project is developed for learning and demonstrating practical applications of AI using Python and the OpenAI API.*

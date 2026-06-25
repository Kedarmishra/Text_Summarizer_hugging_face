# Text Summarizer using Hugging Face

## About

This is a text summarization web application built using the T5 model from Hugging Face Transformers. The project takes a long piece of text as input and generates a shorter summary.

The backend is developed using FastAPI, and the frontend is built with HTML, CSS, and JavaScript.

## Features

* Text summarization using T5
* FastAPI backend
* Simple web interface
* REST API for summarization

## Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* FastAPI
* HTML
* CSS
* JavaScript

## Project Structure

```text
.
├── app.py
├── requirements.txt
├── text_summarizer.ipynb
├── templates/
│   └── index.html
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Text_Summarizer_hugging_face.git
```

Go to the project folder:

```bash
cd Text_Summarizer_hugging_face
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python -m uvicorn app:app --reload
```

Open the browser and visit:

```
http://127.0.0.1:8000
```

## Note

The trained model is not included in this repository because it is too large. You can train the model using the notebook or place the downloaded model inside the `saved_summary_model` folder before running the application.

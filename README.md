# Final project

**Repository name:** `oaqjp-final-project-emb-ai`

## Project name

Final project: Emotion Detection Application using the Watson NLP Library

## Overview

This project implements an emotion detection application using Python, Flask, and the IBM Watson NLP library. The application analyzes user-provided text and returns scores for the following emotions:

- anger
- disgust
- fear
- joy
- sadness
- dominant emotion

## Repository

The public GitHub repository for this project is named:

`oaqjp-final-project-emb-ai`

## Project structure

```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── test_emotion_detection.py
├── server.py
└── README.md
```

## Features

- Emotion detection using the Watson NLP library
- Formatted JSON-style output
- Package-based import validation
- Unit tests for emotion detection
- Flask web deployment
- Error handling for blank or invalid input
- Static code analysis with PyLint

## Running the application

Install the required dependencies and start the Flask server:

```bash
python3 server.py
```

Then open the deployed application in a browser.

## Testing

Run the unit tests with:

```bash
python3 -m unittest test_emotion_detection.py
```

## Static code analysis

Run PyLint with:

```bash
pylint server.py

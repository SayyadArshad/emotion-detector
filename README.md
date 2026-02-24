# Emotion Detector Web Application

## Overview

This project is a simple AI-based web application that detects human emotions from text input.
The application uses the IBM Watson NLP Emotion Prediction model to analyze user text and returns the emotional tone.

The system is implemented as a Python package and deployed as a Flask web application.

---

## Features

* Detects emotions from user text
* Returns dominant emotion with confidence scores
* Flask web interface
* Error handling for empty input
* Unit tested functionality
* Static code analysis using pylint

---

## Project Structure

```
emotion-detector/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── templates/
│   └── index.html
│
├── test_emotion_detection.py
├── server.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/emotion-detector.git
cd emotion-detector
```

Create virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate     # Linux / Mac
venv\Scripts\activate        # Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the Flask server:

```bash
python server.py
```

Open browser and visit:

```
http://localhost:5000
```

---

## Running Unit Tests

```bash
python -m unittest test_emotion_detection.py
```

---

## Static Code Analysis

```bash
pylint server.py
```

---

## Example Output

Input:

```
I am very happy today!
```

Output:

```
Dominant Emotion: Joy
```

---

## Author

Student Software Engineer Project

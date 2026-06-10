# Emotion Detector

## Description
This project is an AI-based web application that detects emotions in text input. It utilizes the **Watson NLP library** to perform sentiment and emotion analysis (such as joy, sadness, anger, fear, and disgust). The application features a clean web interface powered by **Flask**, robust error handling for invalid inputs, and passes all required unit tests and static code analysis standards.

## Technologies Used
- Python
- Watson NLP Library
- Flask (Web Framework)
- Unittest (Testing Framework)
- Pylint (Static Code Analysis)

## Features
- **Emotion Analysis:** Analyzes provided text to return dominant emotion scores.
- **Web Deployment:** A user-friendly web interface to interact with the model.
- **Error Handling:** Validates input and provides clear feedback for empty or invalid requests.
- **Validated Code:** Fully unit-tested and linted for quality and reliability.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python3 server.py`
4. Access the application at `http://localhost:5000`

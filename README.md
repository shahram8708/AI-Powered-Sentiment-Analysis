### README for Advanced AI Sentiment Analysis Web Application

# Advanced AI Sentiment Analysis

Welcome to the Advanced AI Sentiment Analysis tool! This application leverages advanced machine learning algorithms to analyze the sentiment of the provided text, determining whether it is positive, negative, or neutral. Designed with a professional and visually appealing user interface, this tool offers a seamless user experience.

## Features

- **AI-Powered Sentiment Analysis**: Utilize the power of TextBlob to perform sentiment analysis on any given text.
- **Elegant UI**: A modern and sleek user interface with a unique gradient background and professional design elements.
- **Real-time Analysis**: Get instant sentiment analysis results without refreshing the page.
- **Copy & Audio Features**: Easily copy the sentiment result to the clipboard or have it read aloud.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework in Python for building the backend.
- **TextBlob**: A simple NLP library for Python for processing textual data.
- **HTML/CSS/JavaScript**: Frontend technologies for creating a responsive and interactive user interface.
- **jQuery**: A fast, small, and feature-rich JavaScript library for simplifying HTML document traversal and manipulation.

## Setup and Installation

Follow these steps to set up and run the project locally:

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation Steps

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/shahram8708/AI-Powered-Sentiment-Analysis.git
    cd advanced-ai-sentiment-analysis
    ```

2. **Create a Virtual Environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```sh
    pip install Flask TextBlob
    ```

4. **Download NLTK Corpora (if not already installed)**:
    ```sh
    python -m textblob.download_corpora
    ```

5. **Run the Flask Application**:
    ```sh
    python app.py
    ```

6. **Open the Application in Your Browser**:
    Navigate to `http://127.0.0.1:5000/` in your web browser.

## Project Structure

```
advanced-ai-sentiment-analysis/
│
├── templates/
│   └── index.html        # The main HTML file for the web page
│
├── app.py                # The main Flask application
│
├── requirements.txt      # The list of dependencies (optional, if you want to use it for pip install)
│
└── README.md             # This README file
```

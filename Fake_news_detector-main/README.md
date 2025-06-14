Fake News Detector

A Python-based fake news detection tool using machine learning models (Naive Bayes, Random Forest, SVM) with a Flask web interface. Analyzes news articles, predicts authenticity, and highlights potential fake content.

Features

Trains on a subsampled dataset from Fake-1.csv and True-1.csv.
Uses TF-IDF vectorization and three ML models.
Web app displays predictions with probabilities and highlights fake-indicative words in red.
Runs locally with an auto-opening browser interface.

Prerequisites

Python 3.x
Required libraries: pandas, numpy, scikit-learn, flask

Installation

1. Clone the repository:
2. Install dependencies:

3. Usage

Run the script:

The Flask server starts, and a browser opens at http://127.0.0.1:5001.
Enter a news article, select a model, and click "Analyze" to see results.

Example Output

Naive Bayes: 91% accuracy

Random Forest: 98.7% accuracy
SVM: 98% accuracy

Notes
Dataset must be provided by the user.
Designed for macOS/Windows/Linux with automatic browser launch.

License
MIT License - see  file.

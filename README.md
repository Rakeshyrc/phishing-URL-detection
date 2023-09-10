# phishing-URL-detection
# URL Classification Web Application

This is a web application developed in Python using the Flask framework for classifying URLs as 'good' or 'bad.' It leverages machine learning techniques to provide real-time URL classification.

## Overview

The purpose of this project is to create a user-friendly tool that allows users to enter a URL, and the system will classify it based on its characteristics. The system uses a trained logistic regression model and TF-IDF vectorization to make predictions.

**Note:** The prediction model's accuracy is a work in progress, and we are continuously refining it for better performance. Contributions and suggestions for improving the model are highly appreciated.

## Features

- User-friendly web interface for URL classification.
- Custom URL tokenizer for preprocessing input data.
- Trained machine learning model for classification.
- Real-time predictions and results display.

## Getting Started

To run this web application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages 
3. Run the Flask application with `python app.py`.
4. Access the web application in your web browser at `http://localhost:5000/`.

## Usage

1. Enter a URL into the input field on the web page.
2. Click the "Classify" button.
3. The system will classify the URL as 'good' or 'bad' and display the result.

## Dependencies

- Flask: Web framework for creating the application.
- scikit-learn: Machine learning library for model training and prediction.
- pandas: Data manipulation library for handling the dataset.
- numpy: Numerical operations library for data processing.

## Contributing

Contributions are welcome! If you have any ideas, bug fixes, or suggestions for improving the prediction model, please open an issue or submit a pull request.


## Acknowledgments

- The project was inspired by the need to provide users with a simple tool for URL classification.
- Special thanks to the Flask and scikit-learn communities for providing excellent resources and documentation.

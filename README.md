# Cancer Prediction Web Application

## Overview

This is a web application for predicting cancer based on input features. It utilizes a machine learning model to provide predictions and probabilities for cancer diagnosis.

## Project Structure

The project is structured as follows:

- `application.py`: The main Flask application that handles HTTP requests and serves the web interface.
- `src/pipelines`: This directory contains the prediction pipeline.
  - `prediction_pipeline.py`: Contains the machine learning model and prediction logic.
- `templates`: This directory contains HTML templates for rendering web pages.
  - `index.html`: The home page for the web application.
  - `prediction.html`: The page displaying the prediction result.

 ## Getting Started

To run the web application locally, follow these steps:

1. Clone the repository:
```markdown
   ```bash
   git clone <repository_url>
   cd cancer-prediction
   ```

2. Install the required dependencies. It's recommended to use a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Start the Flask application:

   ```bash
   python application.py
   ```

4. Open a web browser and go to `http://localhost:5000` to access the web application.

## Usage

1. On the home page, you'll find a form where you can input various features related to cancer diagnosis.

2. Fill in the feature values and click the "Predict" button.

3. The application will use the machine learning model to predict the diagnosis and display the result on the prediction page.

## Dependencies

- Flask: The web framework used for building the application.
- Other Python libraries used for data processing and machine learning.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to the developers of Flask and the machine learning libraries used in this project.

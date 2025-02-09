# PhishAlert: A Phishing Detector

## Overview

PhishAlert is a web-based application designed to detect phishing attempts in URLs and SMS messages using machine learning algorithms. The project leverages Multinomial Naive Bayes and Logistic Regression to identify and classify phishing websites and spam SMS messages. The goal of PhishAlert is to provide a user-friendly platform that enhances cybersecurity by proactively detecting and mitigating phishing threats in real-time.

## Features

- Phishing Website Detection: The system analyzes website URLs and content to identify phishing attempts using machine learning models.
- Spam SMS Detection: The application can classify SMS messages as spam or legitimate, helping users avoid malicious content.
- User-Friendly Interface: PhishAlert offers an intuitive web interface where users can submit URLs or SMS content for analysis.
- Real-Time Monitoring: The system continuously monitors and flags suspicious activity, providing real-time protection against phishing attacks.
- Feature Importance Analysis: The project explores the importance of individual features in distinguishing between phishing and legitimate content, providing insights into key indicators of phishing behavior.

## How It Works

1. Data Collection: The system gathers a diverse dataset of both phishing and legitimate websites and SMS messages.
2. Preprocessing: The raw data undergoes preprocessing, including cleaning, normalization, and handling missing values.
3. Feature Extraction: Informative features such as website URLs, sender information, suspicious keywords, and linguistic patterns are extracted.
4. Model Training: The system trains Multinomial Naive Bayes and Logistic Regression models to recognize patterns indicative of phishing behavior.
5. Evaluation: The models are evaluated using metrics like accuracy, precision, recall, and F1-score to ensure effective detection.
6. Deployment: The trained models are deployed in real-time environments to monitor websites and SMS messages for potential phishing threats.

## Technical Specifications

- Frontend: Developed using FastAPI and Jinja2Templates for rendering HTML templates.
- Backend: Python scripts handle text preprocessing, feature extraction, and model integration. Libraries like NLTK, scikit-learn, and pickle are used for natural language processing, machine learning, and model serialization.
- Deployment: The application is deployed using Uvicorn, a lightning-fast ASGI server, and hosted on a web server accessible via standard web browsers.

## Key Advantages

- Effective Detection: The use of machine learning algorithms enhances the accuracy of phishing detection.
- Robustness: The models are robust and reliable, capable of handling diverse datasets and mitigating the impact of noise and outliers.
- Scalability: The system is scalable and can process large volumes of data in real-time.
- Interpretability: The models provide interpretable results, allowing users to understand the rationale behind the predictions.
- Feature Importance: The system identifies key features that contribute to phishing detection, guiding future data collection and feature engineering efforts.

## Results

PhishAlert has demonstrated high accuracy in detecting phishing websites and spam SMS messages. The Multinomial Naive Bayes and Logistic Regression models achieved superior performance in distinguishing between legitimate and malicious content, with high precision, recall, and F1-scores. The system's ability to identify key indicators of phishing behavior has provided valuable insights for cybersecurity practitioners.

## Future Scope

- Deep Learning Integration: Future work could explore the integration of deep learning techniques to further enhance detection capabilities.
- Real-Time Response Optimization: Efforts can be made to improve real-time response times and reduce reliance on external services.
- Cross-Platform Compatibility: The system could be adapted to work across different devices and platforms, providing broader protection against phishing attacks.



## Installment Steps:
1. Run the following command to install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
2. Start the prediction application with this command:
    ```bash
    python prediction_app.py
    ```

# Candidate Selection using NLTK and ML Algorithms

This repository contains code that demonstrates how to use Natural Language Toolkit (NLTK) and scikit-learn library to find the correct candidate for a job using Machine Learning (ML) algorithms.

## Problem Statement

The task is to develop a program that can analyze candidate profiles and job descriptions to identify the most suitable candidate for a given job. The solution involves using ML algorithms, NLTK for natural language processing, and scikit-learn for ML model training.

## Code Overview

The code follows the following steps:

1. Data Collection: We collect job descriptions and candidate profiles as lists of strings.

2. Data Preprocessing: The text data is preprocessed using NLTK. The steps include converting text to lowercase, tokenization, removing non-alphabetic tokens, and eliminating stop words.

3. Feature Extraction: The preprocessed text is transformed into numerical features using the TF-IDF vectorization technique provided by scikit-learn.

4. Training Data Preparation: The dataset is split into training and validation sets to train and evaluate the ML model.

5. ML Algorithm Selection and Training: Logistic regression is chosen as the ML algorithm, and the model is trained using the training data.

6. Model Evaluation: The model's performance is evaluated by making predictions on the validation set and calculating the accuracy.

7. Prediction for New Candidate Profile: A new candidate profile can be provided as input, and the trained model predicts the suitability of the candidate for the job.

## Usage

To use this code, follow these steps:

1. Ensure that you have Python installed on your system along with the necessary libraries mentioned in the requirements.txt file.

2. Clone this repository to your local machine.

3. Modify the job descriptions and candidate profiles in the code to match your specific use case.

4. Run the code and observe the validation accuracy and prediction for the new candidate profile.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to create a pull request or open an issue.

## License

This code is licensed under the [MIT License](LICENSE).

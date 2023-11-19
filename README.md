# Phishing Website Detection using Neural Networks

## Project Overview
This project focuses on the development of a machine learning model to identify phishing websites. Utilizing a neural network, the model classifies websites into 'phishing' or 'non-phishing' categories based on various features extracted from URLs.

## Motivation
Phishing attacks are a prevalent issue in cybersecurity, where attackers lure individuals into providing sensitive data. This project aims to contribute to digital security by accurately identifying and flagging potential phishing websites.

## Dataset
The dataset used in this project includes various features extracted from website URLs. Each entry in the dataset is labeled as 'phishing' or 'non-phishing'.

## Methodology
The project involves the following steps:
1. Data Preprocessing: Cleansing and transforming raw data into a suitable format for the model.
2. Feature Engineering: Selecting and engineering features from URLs that are indicative of phishing activities.
3. Model Training: Training a neural network model to classify websites.
4. Evaluation: Assessing the model's performance using metrics like accuracy, precision, recall, and F1-score.

## Technologies Used
- **Python**: Primary programming language
- **TensorFlow and Keras**: For building and training the neural network model
- **Scikit-learn**: For data preprocessing and model evaluation
- **Pandas and NumPy**: For data manipulation and numerical computations
- **Matplotlib and Seaborn**: For data visualization

## Results
The model achieved an accuracy of approximately 92.86% on the validation set, indicating strong performance in distinguishing between phishing and non-phishing websites.

## How to Use
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks to train the model and make predictions.

## Future Work
Future improvements might include experimenting with different machine learning algorithms, enhancing feature engineering, and using a larger dataset for training.

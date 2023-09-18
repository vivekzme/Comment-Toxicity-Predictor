# Comment-Toxicity-Predictor


# Toxic Comment Detection with Deep Learning

![GitHub repo size](https://img.shields.io/github/repo-size/YourUsername/Toxic-Comment-Detection)
![GitHub stars](https://img.shields.io/github/stars/YourUsername/Toxic-Comment-Detection?style=social)
![GitHub forks](https://img.shields.io/github/forks/YourUsername/Toxic-Comment-Detection?style=social)

A deep learning model for detecting toxic comments/statements in text using Keras and TensorFlow.

## Overview

This project involves the construction and training of a deep learning model to identify toxic comments or statements within text data. The model is developed using Keras and TensorFlow and was trained on a dataset comprising nearly 160,000 comments, categorized as toxic or non-toxic.

## Key Features

- Constructed and trained a deep learning model for detecting toxic comments/statements.
- Utilized Keras and TensorFlow to train the model.
- Employed text vectorization with a batch size of 16 to create word embeddings.
- Achieved an initial F1 score of 0.73.
- Enhanced the F1 score to 0.94 using Bidirectional LSTM layers trained over 16 epochs.

## Dataset

The dataset used for training and evaluation contains a diverse set of comments, including both toxic and non-toxic comments. The model's performance was measured using various evaluation metrics, with a primary focus on F1 score, which reflects the model's ability to balance precision and recall.

## How to Use

1. Clone this repository to your local machine.


2. Navigate to the project directory.

3. Follow the instructions in the project's Jupyter notebook or Python scripts to train the model or perform inference on your own data.

## Results

- Initial F1 Score: 0.73
- Final F1 Score: 0.94 (after 16 epochs of training)

## Contributions

Contributions to this project are welcome! If you have any ideas for improvements or want to report issues, please feel free to open an issue or submit a pull request.


---

You can use this template by creating a new README.md file in your GitHub repository and replacing "YourUsername" with your actual GitHub username or organization name. You can also add more details, sections, or customizations as needed.


<h1 align="center" id="title">Tweet Emotion Recognition: Natural Language Processing with TensorFlow</h1>

<div align="center">
  <img src="https://www.icegif.com/wp-content/uploads/2022/03/icegif-784.gif" alt="Centered GIF">
</div>


## Overview

This project focuses on the development of a deep learning model for tweet emotion recognition using TensorFlow and Long Short-Term Memory (LSTM) networks. The model can categorize tweets into various emotional states, such as sadness, joy, love, anger, fear, and surprise.

## Table of Contents

- [Dataset](#dataset)
- [Methodology](#methodology)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Usage](#usage)
- [Potential Use Cases](#potential-use-cases)
- [Contributing](#contributing)
- [License](#license)

## Dataset

We utilized the [Tweet Emotion Dataset](https://github.com/dair-ai/emotion_dataset) for training and testing the emotion recognition model. The dataset contains a variety of tweets labeled with corresponding emotions.

## Methodology

We followed a structured methodology:

1. Data preprocessing, including tokenization and padding of text data.
2. Model selection: An LSTM model with two Bidirectional layers and a dense layer (softmax) was chosen for its ability to capture contextual information efficiently in both forward and backward directions.
3. Model compilation with 'sparse_categorical_crossentropy' as the loss function, 'adam' as the optimizer, and 'accuracy' as the monitoring metric.
4. Model training for 20 epochs, with early stopping to prevent overfitting.

## Model Architecture

The selected model architecture consists of two Bidirectional LSTM layers followed by a dense layer with softmax activation.

## Results

The model achieved an accuracy of 87.85% in classifying tweets into various emotion categories. The confusion matrix analysis and accuracy assessment validated its effectiveness.

## Usage

To use the model, you can follow the code in the repository provided in this repository. It includes data preprocessing, model training, and evaluation steps.

## Potential Use Cases

1. Brand Sentiment Analysis: Monitor public sentiment towards brands or products on Twitter.
2. Crisis Management: Assess public sentiment during crises or sensitive events for effective response strategies.
3. Social Media Monitoring: Continuously analyze public emotions and opinions on social media platforms for trend analysis and user engagement strategies.
4. Customer Feedback Analysis: Categorize customer feedback on social media to gain insights for product or service improvements.





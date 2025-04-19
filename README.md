# 🎙️ Speaker Recognition using Deep Learning

This project implements a speaker recognition system using MFCC features and a deep learning model (LSTM/CNN-based). It classifies audio samples into different speakers based on their voice characteristics.

---

## 📌 Features

- MFCC feature extraction
- Sequence modeling with LSTM or CNN
- Visualization of training accuracy/loss
- Dropout for regularization
- Speaker classification with high accuracy

---

## 📂 Dataset

We use the [Speaker Recognition Dataset](https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset) from Kaggle, which contains `.wav` audio samples from multiple speakers.

➡️ **Get the data from here:**  
🔗 [https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset](https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset)

---

## 🧠 Model Overview

The model is designed to handle time-series data extracted from audio signals. We use Mel-frequency cepstral coefficients (MFCC) as features and train a deep neural network for classification.

The architecture primarily uses LSTM layers to learn sequential patterns in speech. Dropout layers and batch normalization are used to enhance generalization and prevent overfitting. Alternatively, a CNN-based model can be used for faster inference while maintaining competitive accuracy.

Training progress is monitored using loss and accuracy visualizations. The final model is capable of identifying speakers based on their unique vocal features.




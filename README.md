# Emotion Detection from Audio Signals

This repository contains a Jupyter Notebook that implements an **Emotion Detection System** using the **RAVDESS** (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset. The system classifies emotions such as happiness, sadness, anger, and more based on audio signals using a deep learning model.

## Features
- Audio signal processing using `librosa` to extract MFCC features.
- Preprocessing and encoding of emotion labels.
- Implementation of a dense neural network using TensorFlow/Keras.
- Model evaluation with accuracy metrics and visualizations.

## Dataset

The **RAVDESS** dataset (Ryerson Audio-Visual Database of Emotional Speech and Song) is a high-quality dataset used for emotion recognition tasks. It contains:
- **7356 audio files**, including emotional speech and song recordings.
- **24 professional actors** (12 male, 12 female) performing emotional expressions.
- **8 emotional states**: calm, happy, sad, angry, fearful, surprise, disgust, and neutral.
- Each file is saved as a high-quality `.wav` format.

The dataset is publicly available on [Kaggle](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio). In this project, only the **speech** files are used for emotion detection. The emotional labels are encoded for training the model.

### Dataset Structure
The dataset is organized in folders based on the actor. Each file follows the naming convention:

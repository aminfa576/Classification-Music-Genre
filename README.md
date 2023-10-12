
# Music Genre Classification Using CNNs

## Overview
This repository contains a deep learning project aimed at classifying music genres from audio samples. Using Convolutional Neural Networks (CNNs) and audio processing techniques, the project demonstrates the potential of deep learning in recognizing and categorizing diverse music genres.

## Tasks

1. **Data Preprocessing**: 
   - Audio file processing to extract critical features using the `librosa` library.
   - Extraction of Mel-frequency cepstral coefficients (MFCCs) from audio files for use as primary features.

2. **Model Building**:
   - Development of a CNN model with multiple layers for genre classification.
   - Implementation of regularization and dropout techniques to combat overfitting.
   
3. **Model Training and Testing**:
   - Training the model on the GTZAN dataset.
   - Evaluation of the model's performance using various metrics such as accuracy, precision, recall, and F1-score.
   
4. **Integration with Spotify**:
   - Fetching song previews from the Spotify API for real-world testing.
   - Fine-tuning the model on a diverse set of genres fetched from Spotify.

5. **Experimental Analysis**:
   - Testing the model's performance across various training-test splits.
   - Analysis of the model's adaptability to different numbers of genre classifications.

## Dataset
The primary dataset used is the [GTZAN dataset](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification) available on Kaggle. It contains 1000 audio tracks each 30 seconds long, covering 10 different genres. Additionally, song previews from Spotify were utilized to further test and fine-tune the model.

## Technologies
- **Python**: Primary programming language for data processing and modeling.
- **TensorFlow**: Deep learning framework used to design, train, and test the CNN model.
- **Librosa**: Python library for analyzing and extracting features from audio files.
- **Spotipy**: A lightweight Python library for the Spotify Web API. Used for fetching song previews from Spotify.
- **Scikit-learn**: Machine learning library in Python. Used for data splitting and model evaluation.
- **Matplotlib & Seaborn**: Used for data visualization and plotting model performance metrics.

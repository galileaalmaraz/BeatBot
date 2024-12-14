# BeatBot
BeatBot: Leveraging K-Nearest Neighbors for Music Genre Classification and Audio Analysis

BeatBot: Music Genre Classification with KNN
## Welcome to BeatBot, an interactive application designed to classify music genres and provide song statistics using machine learning techniques and an intuitive user interface.

# Table of Contents
1. Introduction
2. Features
3. Technologies Used
4. How It Works
5. Installation
6. Usage
7. Embedding a Demo Video
8. Acknowledgments

## Introduction
BeatBot is a Python-based application that uses a pre-trained K-Nearest Neighbors (KNN) model to classify music genres. The application also extracts useful song statistics such as tempo, spectral centroid, and spectral rolloff. Its user-friendly interface is powered by Gradio, making it accessible to users with minimal technical expertise.

## Features
- Upload a .wav file for music genre classification.
- Extract and display:
-   Predicted genre.
Tempo (BPM).
Spectral centroid (Hz).
Spectral rolloff (Hz).
Customizable user interface with a sleek black-and-blue theme.
Interactive and responsive via Gradio.
Technologies Used
Machine Learning: KNN model for genre classification.
Audio Processing: librosa for feature extraction and statistical analysis.
Frontend/Backend Interface: Gradio for creating the GUI.
Python Libraries:
joblib: Model persistence.
numpy: Numerical operations.
scikit-learn: Machine learning algorithms.
How It Works
Feature Extraction: Extracts MFCCs, chroma features, and mel spectrogram from uploaded audio using librosa.
Song Statistics: Calculates tempo, spectral centroid, and spectral rolloff to provide additional insights.
Model Prediction: Uses a pre-trained KNN model (knn_model.pkl) to classify the music genre.
User Interaction: Outputs both the predicted genre and song statistics in a user-friendly format.
Installation
Prerequisites

Python 3.8+
Libraries: librosa, numpy, joblib, scikit-learn, gradio
Steps

Clone this repository:
git clone https://github.com/yourusername/BeatBot.git
cd BeatBot
Install the required libraries:
pip install -r requirements.txt
Ensure the knn_model.pkl file is in the working directory.
Usage
Launch the application:
python beatbot.py
A local web interface will appear. Upload a .wav file and view the results.
Embedding a Demo Video
To embed a demo video (e.g., a YouTube video):

Record and upload your demo to YouTube.
Copy the YouTube video ID (e.g., abc123).
Embed the video in your GitHub README using the following syntax:
### Demo
Watch the demo of BeatBot in action:
[![BeatBot Demo](https://img.youtube.com/vi/<video-id>/0.jpg)](https://www.youtube.com/watch?v=<video-id>)
Replace <video-id> with the actual ID of your YouTube video.

Acknowledgments
GTZAN Dataset by Andrada Olteanu: Link
Developers of librosa, gradio, and scikit-learn.
Inspired by the music genre classification research by Tzanetakis and Cook.

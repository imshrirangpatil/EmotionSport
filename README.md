# EmotionSport
Neural-Powered Athletic Performance Analysis System

EmotionSport is a sports facial emotion analysis system. It uses a high-level neural network for emotion detection, such as CNN and Bi-directional LSTM models, to detect and quantify the emotions of each athlete involved in the sport. The idea behind this project is to understand how emotional states reflect in player performances, with data-driven decisions by coaches and trainers.

Features
Emotion Detection: The Emotion Detection features use CNN and Bi-LSTM models.
Performance Insights: Quantified emotional metrics like frequency, intensity, and duration are analyzed for their implications on player performance.
High Accuracy: Achieved as high as 90.67% using the CK+485 Emotion Dataset.

Implemented Models
Simple CNN: Basic CNN for emotion detection.
CNN + Bi-directional LSTM: We combined the CNN with an architecture like the Bi-LSTM to capture past and future emotional context.
ConvLSTM: Hybrid model - Using convolutional layers together with LSTM for better performance in sequence prediction.

Dataset
CK+485 Emotion Dataset: Data used for training and testing; split is 70/30. It was preprocessed, and augmentation was done to enhance model performance.

Important Performance Metrics
Accuracy: Simple CNN: 98.22%, CNN + Bi-LSTM: 90.67%, ConvLSTM: 95.00%
Emotion Metrics: Frequency, Intensity, Duration, Consistency, Correlation

Results
The system provides several visualizations and statistics regarding the emotions of players during matches.
These can then be used by coaches to make necessary adjustments in team dynamics and individual player areas for improvement.

Future Improvement
Integrate more sources of data, body language, voice analysis, etc. Employ attention mechanisms to help the model pay more attention to specific emotional features.

Contributors
Pradyumn Kedar Tendulkar - Team Leader
Sathvick Sudarsan - Data Collection & Model Testing
Shrirang Patil - Model Building
Utkarsh Krishna - Model Training
Aadya Goel - Literature Survey & Presentation
Faiz Shamsudeen Bin Hussain - Research & Business Model

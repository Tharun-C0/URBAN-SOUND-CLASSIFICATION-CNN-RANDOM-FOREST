🎧 Urban Sound Classification

A machine learning project focused on classifying urban sounds using two different approaches:

Convolutional Neural Network (CNN)
Random Forest Classifier

This project was collaboratively developed to compare deep learning and traditional machine learning techniques on audio data.

🚀 Project Overview

Urban environments contain a wide variety of sounds such as sirens, dog barks, drilling, and engine noise.
This project aims to automatically classify these sounds using audio processing and machine learning models.

👨‍💻 Contributors
Tharun C – Implemented CNN Model
Mohamed Ansari – Implemented Random Forest Model
🧠 Models Used
🔹 CNN (Convolutional Neural Network)
Converts audio into spectrogram images
Learns spatial patterns in sound data
Provides higher accuracy for complex audio classification
🔹 Random Forest
Uses extracted features like MFCC
Ensemble learning method (multiple decision trees)
Faster and simpler compared to CNN
⚙️ Tech Stack
Python 🐍
Librosa 🎵 (Audio processing)
NumPy & Pandas
Matplotlib
Scikit-learn
TensorFlow / Keras
🔄 Workflow
Audio Dataset Collection
Preprocessing using Librosa
Feature Extraction (MFCC / Spectrogram)
Model Training
CNN Model
Random Forest Model
Model Evaluation
Result Comparison
📊 Results
CNN model achieved better performance in capturing complex audio patterns
Random Forest performed well with structured features like MFCC
Comparative analysis shows deep learning is more effective for audio classification

👉 Conclusion: CNN outperforms Random Forest for urban sound classification tasks.

📁 Dataset
Urban Sound Dataset (e.g., UrbanSound8K)
Contains labeled environmental audio clips
📌 Features
Dual-model implementation for comparison
Real-world sound classification
Audio-to-spectrogram conversion
Efficient preprocessing pipeline
⚠️ Challenges
Background noise in audio data
Feature extraction complexity
Model tuning and overfitting
Large dataset processing time
🔮 Future Improvements
Use advanced models like LSTM / Transformers
Real-time sound classification system
Deploy as a web/mobile application

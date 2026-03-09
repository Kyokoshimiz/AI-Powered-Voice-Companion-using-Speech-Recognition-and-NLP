# AI-Powered-Voice-Companion-using-Speech-Recognition-and-NLP
A voice assistant based on AI that provides a platform for natural human-computer interaction using speech recognition, NLP-based intent detection, and text-to-speech synthesis. The system listens to the user's command, processes the command using a trained chatbot model, and responds with synthesized speech.

Features
 Speech recognition for voice input
NLP-based intent detection
Text-to-speech response generation
 Neural network–based chatbot model
Model training and evaluation

Technologies Used
Python
NLTK (Natural Language Toolkit)
TensorFlow / Keras
NumPy
Scikit-learn
JSON for dataset storage

AI-Voice-Companion
│
├── train_chatbot.py      # Script for training the chatbot model
├── test_chatbot.py       # Script for testing the chatbot
├── dataset.txt           # Training dataset
├── new.json              # Intents dataset
├── classes.pkl           # Stored intent classes
├── README.md             # Project documentation

How It Works

Dataset Preparation
Intents and patterns are stored in a new.json file.
Text Processing
Text is tokenized using NLTK.
Text is lemmatized, and vectors are created.
Model Training
A Neural Network model is created using Keras.
The model is trained to recognize patterns of different intents.
Prediction
User text is processed, and it is passed into the model.
The model predicts the most relevant intent.

Response Generation
A response is chosen by the chatbot.

The response is converted into speech using TTS.

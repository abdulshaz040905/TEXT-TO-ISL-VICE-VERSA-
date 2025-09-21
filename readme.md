ISL Translator

Two-way Indian Sign Language (ISL) translation system for communication between Normal Users (Hindi/English) and Deaf Users (ISL).

Implementation
Normal → Deaf

Input: Text / Speech

Tools: React/Next.js (UI), Whisper/Vosk (speech-to-text)

Process: NLP translation → Gesture mapping → Avatar animation

Output: ISL gestures on avatar (Three.js / Unity)

Deaf → Normal

Input: ISL gestures via camera

Tools: MediaPipe/OpenPose + CNN/LSTM (gesture recognition)

Process: NLP translation → Text/Speech

Output: Hindi/English text or speech

Backend

API / Model Serving: FastAPI / Flask, PyTorch/TensorFlow

Database: SQLite/Postgres (gesture mapping & logs)

Dataset

ISLRTC + custom videos for training NLP & gesture recognition

Frontend

React/Next.js, Three.js / Unity for 3D avatar, webcam/audio capture

Goal

Real-time two-way communication between Normal and Deaf users using ISL, speech, and text.
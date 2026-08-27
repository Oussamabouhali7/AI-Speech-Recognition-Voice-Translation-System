# AI Speech Recognition & Transcription System

## 📌 Overview

This project focuses on the development of an **AI-powered speech recognition and transcription system** using Deep Learning and Natural Language Processing techniques.

The system enables users to convert speech into text, compare different speech recognition models, and evaluate their performance using dedicated metrics.

The project was developed as part of the **PCD 2025 at ENSI**, under the supervision of **Marouene Chaieb**, in collaboration with **Oussama Bouhali, Karim Lazghab, and Omar Jabri**.

---

## 🎯 Objectives

* Develop an automatic speech recognition and transcription system.
* Convert spoken language into text using Deep Learning models.
* Compare different neural network architectures for speech recognition.
* Evaluate model performance using **Accuracy, WER, and CER**.
* Provide an interactive solution for speech transcription and translation.
* Explore the use of **OpenAI Whisper** for speech recognition.

---

## 🎙️ Main Features

The application provides two methods for speech input:

### 📁 Audio File Upload

Users can upload a recorded audio file and obtain its transcription.

### 🎤 Microphone Recording

Users can directly record their voice through the microphone and generate the corresponding transcription.

### 🌍 Translation

Users can select a **target language** and obtain:

* Original transcription
* Translated transcription
* Translated voice output

---

## 🤖 Speech Recognition Models

Several Deep Learning architectures were implemented and evaluated:

* **RNN**
* **LSTM**
* **GRU**
* **Transformer**
* **OpenAI Whisper**

The objective is to compare different architectures and identify the most effective approach for speech recognition.

---

## 📊 Model Evaluation

The implemented models are evaluated using several performance metrics:

* **Accuracy**
* **WER — Word Error Rate**
* **CER — Character Error Rate**

A comparison of the models is performed to analyze their strengths and weaknesses in terms of transcription accuracy and error rates.

---

## 📈 Model Comparison

The project includes dedicated notebooks for the implementation and evaluation of each architecture:

| Model       | Notebook                 |
| ----------- | ------------------------ |
| RNN         | `RNN_code.ipynb`         |
| LSTM        | `LSTM_code.ipynb`        |
| GRU         | `GRU_code.ipynb`         |
| Transformer | `Transformer_code.ipynb` |
| Whisper     | `Whisper_code.ipynb`     |

The main system implementation is available in:

`Speech_recognition_system_building.ipynb`

---

## 🔐 Authentication & User Management

The complete application includes an authentication system with:

* User registration
* Login / Logout
* PostgreSQL database integration
* User accounts
* Admin accounts
* User management
* CRUD operations for administrators

The **Admin** role provides additional functionalities for managing registered users.

---

## 🏗️ System Workflow

```text
Audio File / Microphone
          ↓
   Speech Recognition
          ↓
   Preprocessing
          ↓
 Deep Learning Model
          ↓
   Original Transcription
          ↓
    Target Language
          ↓
    Translation
          ↓
 Translated Transcription
          ↓
   Translated Speech
```

---

## 🛠️ Technologies

### Programming & Data Science

* Python
* NumPy
* Pandas

### Deep Learning

* RNN
* LSTM
* GRU
* Transformer
* Whisper

### Natural Language Processing

* Speech Recognition
* Speech-to-Text
* Machine Translation
* Text-to-Speech

### Database

* PostgreSQL

### Application

* User Authentication
* Admin Dashboard
* CRUD Operations
* Interactive Interface

---

## 📂 Repository Contents

This repository contains the different notebooks used throughout the project:

* `RNN_code.ipynb` — RNN implementation
* `LSTM_code.ipynb` — LSTM implementation
* `GRU_code.ipynb` — GRU implementation
* `Transformer_code.ipynb` — Transformer implementation
* `Whisper_code.ipynb` — Whisper-based speech recognition
* `speech_recognition_system_building.ipynb` — Complete speech recognition system
* `README.md` — Project documentation

---

## 🎥 Application Demo

A complete demonstration of the application is available on LinkedIn.

The demo showcases:

* Audio file transcription
* Microphone-based transcription
* Language selection
* Original and translated transcription
* Voice translation
* User authentication
* Admin functionalities
* Model comparison and evaluation dashboard

**[▶️ Watch the application demo on LinkedIn](YOUR_LINKEDIN_POST_URL)**

---

## 👥 Team

**Oussama Bouhali**
**Karim Lazghab**
**Omar Jabri**

### Supervisor

**Marouene Chaieb**

---

## 🎓 Academic Project

**PCD 2025 — École Nationale des Sciences de l'Informatique (ENSI)**

This project combines **Artificial Intelligence, Deep Learning, Speech Recognition, NLP, Machine Learning, and Database Management** to develop an end-to-end speech processing solution.

**[LSTM_code.ipynb]

---

## ⚠️ Disclaimer

This project was developed for **academic and educational purposes** as part of the PCD 2025 project at ENSI.

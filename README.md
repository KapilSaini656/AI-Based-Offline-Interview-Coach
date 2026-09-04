# 🎤 AI-Based Offline Interview Coach

An intelligent interview preparation platform that analyzes spoken interview responses and provides automated feedback on **communication quality, confidence, fluency, grammar, sentiment, and answer relevance**.

Unlike traditional cloud-based interview tools, this system performs all processing **locally on the user's machine**, ensuring complete privacy while delivering AI-powered insights through speech processing and Natural Language Processing (NLP) techniques.

---

## 🚀 Key Features

### 🎙 Speech-to-Text Transcription

Converts spoken interview responses into text using **OpenAI Whisper** for accurate offline transcription.

### 📊 Communication Analysis

Evaluates important speaking metrics, including:

- **Speaking Rate** (Words Per Minute)
- **Pause Duration Analysis**
- **Fluency Assessment**
- **Confidence Indicators**

### 🧠 NLP-Powered Feedback

Generates detailed feedback using multiple NLP models and techniques:

- **Grammar Analysis** using LanguageTool
- **Sentiment Analysis** using DistilBERT
- **Semantic Answer Relevance** using Sentence-BERT
- **Structured Interview Performance Evaluation**

### 🔒 Privacy-First Architecture

All processing is performed locally on the user's machine.

- **No cloud APIs**
- **No external data sharing**
- **No interview recordings uploaded**
- **Fully offline operation after model download**

### 📈 Interactive Feedback Dashboard

Provides visual performance insights through:

- **Confidence Score**
- **Fluency Score**
- **Grammar Score**
- **Relevance Score**
- **Overall Interview Performance Summary**

---

## 🏗 System Workflow

```text
Interview Response
        ↓
Audio Recording
        ↓
Whisper Speech-to-Text
        ↓
Audio Feature Extraction
        ↓
NLP Analysis
        ↓
Performance Scoring
        ↓
Feedback Dashboard

---
```

## 🛠 Technology Stack

### Frontend

- **HTML5**
- **CSS3**
- **JavaScript**
- **MediaRecorder API**

### Backend

- **Flask**

### Speech Processing

- **OpenAI Whisper**
- **Librosa**

### Natural Language Processing

- **DistilBERT**
- **Sentence-BERT**
- **LanguageTool**

### Machine Learning

- **Transformers**
- **Sentence Transformers**

---

## ⚙️ Installation

### Prerequisites

Before running the project, make sure the following are installed:

- **Python 3.9+**
- **Java** — Required for LanguageTool
- **FFmpeg** — Required by Whisper

### Install Dependencies

Navigate to the backend directory:

```bash
cd backend
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Run Backend

Navigate to the backend directory:

```bash
cd backend
```

Start the Flask server:

```bash
python app.py
```

The backend server should now be running.

### Run Frontend

Open a **new terminal** and navigate to the frontend directory:

```bash
cd frontend
```

Start the local frontend server:

```bash
python -m http.server 8000
```

Open the application in your browser:

```text
http://localhost:8000
```

---

## 🔐 Privacy

This project is designed with a **privacy-first approach**.

Audio recordings, transcripts, and evaluation results remain on the user's device and are never transmitted to external servers.

The system is designed to perform its core processing locally without relying on cloud-based interview analysis services.

---

## 🎯 Future Enhancements

Planned improvements include:

- **Personalized interview question generation**
- **Domain-specific interview preparation**
- **Real-time speech coaching**
- **Multilingual interview analysis**
- **AI-generated improvement suggestions**

---

## 📂 Project Structure

```text
AI-Based-Offline-Interview-Coach/
│
├── backend/
│   ├── app.py
│   ├── audio_processing.py
│   ├── nlp_analysis.py
│   ├── requirements.txt
│   └── scoring.py
│
├── frontend/
│   ├── analysis.html
│   ├── feedback.html
│   ├── index.html
│   ├── recording.html
│   └── setup.html
│
├── .gitignore
├── README.md
├── extract.py
├── plot_results.py
├── prd.txt
└── read_docx.py
```

---

## 💡 Project Objective

The goal of **AI-Based Offline Interview Coach** is to provide candidates with an intelligent and private environment for improving their interview performance.

Instead of relying on external interview platforms, users can record their responses locally and receive structured feedback on their **speech, communication, language quality, confidence, sentiment, and answer relevance**.

This makes the platform particularly useful for students, job seekers, and professionals preparing for interviews while maintaining control over their personal interview data.

---



# 🎙️ Speech to Indian Sign Language Conversion using AI

A complete AI-based system that converts spoken language (from YouTube videos) into **Indian Sign Language (ISL)** representations using **Natural Language Processing (NLP)**, **Speech Recognition**, and **Computer Vision–based visualizations**.

---

## 📖 Overview

This project aims to improve accessibility for the deaf and hard-of-hearing community by translating speech into understandable **Indian Sign Language formats**.  
It processes audio from videos, transcribes speech into text, analyzes emotions, converts text into ISL-friendly glosses, and visualizes the output using fingerspelling GIFs and sign representations.

---

## 🧠 Technologies & Concepts Used

### 🔹 Natural Language Processing (NLP)
- Text preprocessing (tokenization, normalization)
- Stop-word removal and keyword extraction
- ISL-oriented grammar simplification

### 🔹 Speech Recognition
- Converts speech → text using **OpenAI Whisper**
- Supports real-world YouTube audio with noise

### 🔹 Emotion Analysis
- Sentiment & emotion detection from transcribed text
- Helps convey tone and context

### 🔹 Sign Language Generation
- Letter-wise fingerspelling (A–Z, numbers)
- Word-wise and sentence-wise visualization
- Token-based and fast combined animations

### 🔹 Visualization
- GIF generation using image frames
- Streamlit-based interactive UI

---

## ⚙️ System Workflow

1. Input: YouTube video URL  
2. Audio extraction (FFmpeg)  
3. Speech → text transcription  
4. Emotion & NLP processing  
5. ISL gloss generation  
6. Fingerspelling & sign visualization  
7. Downloadable output  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- OpenAI Whisper  
- FFmpeg  
- NLP techniques  
- Computer Vision  

---

## 🚀 How to Run the Project

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py 
```


## 📌 Features

✔ Real-time speech transcription  
✔ Emotion-aware sign generation  
✔ Letter-wise & word-wise fingerspelling  
✔ Accessible UI for learning ISL  
✔ Modular & scalable architecture  

---

## 🎯 Use Cases

- Accessibility tools for deaf users  
- Educational ISL learning platforms  
- Smart classrooms  
- Assistive AI systems  

---

## 👩‍💻 Author

**Srishti Raj**  
B.Tech Computer Science Engineering  
Vellore Institute of Technology  

---

## 📜 License

This project is for educational and research purposes.

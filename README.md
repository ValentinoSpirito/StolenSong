# WhoStoleMySong

![Lizenz](https://img.shields.io/badge/license-MIT-blue.svg)

This Python project uses machine learning to find similar sounding songs with a music database.

---

## 🎯 About The Project
Have you ever listened to a song and thought, "this sounds just like a song I heard the other day?".
This project aims to solve exactly this problem. It takes a song as input, analyzes its acoustic properties and searches a pre-computed database to find the track with the highest sonic similarity

The core of this project is **Content-Based Audio Retrieval**. Instead of comparing metrics of a song like "genres" and "artist", the audio file (.mp3) is converted into a numerical "fingerprint" (a feature vector) and compared directly.

### ⚒️ Built With
* **Python 3.x**
* **Librosa:** For audio analysis and feature extraction (MFCCs).
* **Scikit-learn:** For calculating similarity (Cosine Similarity).
* **NumPy:** For efficient numerical data handling.
* **Pandas:** For preprocessing and organizing song metadata.

---

## 📜 License
Distributed under the MIT License. See the 'LICENSE' file for more information.

---

## 💫 Acknowledgements
* Thank you to all the artists that steal their songs (partially) and therefor gave me the inspiration for this project.
* [FMA (Free Music Archive) Dataset](https://github.com/mdeff/fma) for providing the audio data.

# 🧠 Emotion Detector From Text

A Streamlit-based web application that detects emotions from text using the Hugging Face Transformer model **j-hartmann/emotion-english-distilroberta-base**.

## ✨ Features

- 🔍 Detects emotions from user input text
- 🤖 Powered by Hugging Face Transformers
- 🎨 Interactive Streamlit interface
- 🎭 Displays emotion-specific GIFs
- ⚡ Real-time predictions

## 🛠️ Tech Stack

- Python
- Streamlit
- Hugging Face Transformers
- PyTorch

## 📂 Project Structure

```
emotion-detector/
│
├── app.py              # Main application
├── requirements.txt    # Dependencies
└── .gitignore
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/emotion-detector.git
cd emotion-detector
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run app.py
```

## 🧪 Example

Input:

```
I'm feeling very happy today!
```

Output:

```
Emotion: JOY 😊
```

## 📸 Features Supported

- Joy 😀
- Happiness 😄
- Sadness 😢
- Anger 😡
- Fear 😨
- Surprise 😲
- Disgust 🤢
- Neutral 😐
- Excitement 🤩
- Loneliness 😔

## 🤖 Model Used

**j-hartmann/emotion-english-distilroberta-base**

A transformer-based emotion classification model available on Hugging Face.

## 📦 Requirements

- Python 3.9+
- Streamlit
- Transformers
- Torch

Install all dependencies with:

```bash
pip install -r requirements.txt
```

## 🎯 Future Improvements

- Speech emotion detection
- Multilingual support
- Emotion analytics dashboard
- Voice input support
- Sentiment + emotion combined analysis

## 📜 License

This project is open-source and available under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!

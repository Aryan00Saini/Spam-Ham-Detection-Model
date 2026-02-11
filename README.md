📩 Spam Detector – Machine Learning Desktop Application

A modern, machine learning–powered desktop application that classifies text messages as SPAM 🚫 or HAM ✅ with real-time probability scores.

---

🚀 Overview

Spam Detector is a Python-based desktop application built using Natural Language Processing (NLP) and Machine Learning.
It uses TF-IDF vectorization and a Multinomial Naive Bayes classifier to accurately detect whether a message is spam or legitimate.

The application features a full-screen responsive interface with animated background effects, making it both technically strong and visually appealing.

---

✨ Key Features

🧠 ML-Based Classification – Uses TF-IDF + Multinomial Naive Bayes

⚡ Real-Time Prediction – Instant spam detection

📊 Confidence Score Display – Shows probability percentage

🎨 Modern Animated GUI – Particle animation background

🔄 Pre-trained Model Loading – Uses saved .pkl files

🧹 Automatic Text Preprocessing – Lowercasing & punctuation removal

🖥 Full-Screen Responsive Interface


---

🛠 Tech Stack

| Technology      | Purpose                |
| --------------- | ---------------------- |
| 🐍 Python       | Core Programming       |
| 🤖 Scikit-learn | Machine Learning Model |
| 📊 TF-IDF       | Text Vectorization     |
| 🖥 Tkinter      | GUI Development        |
| 💾 Pickle       | Model Serialization    |


---


📂 Project Structure
```plaintext
Spam-Detector/
│
├── Spam.py
├── spam_model/
│   ├── model.pkl
│   └── tfidf.pkl
└── README.md
```

---

🧠 How It Works

User enters a message in the input field.

Text is preprocessed:

Converted to lowercase

Punctuation removed

TF-IDF converts text into numerical feature vectors.

The trained Naive Bayes model predicts:

SPAM 🚫

HAM ✅

The result is displayed with probability confidence.

---

⚙️ Installation & Setup
1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/spam-detector.git
cd spam-detector
```
2️⃣ Install Dependencies
```bash
pip install numpy pandas scikit-learn
```

3️⃣ Add Model Files

Ensure the following files are placed inside the spam_model/ directory:

model.pkl

tfidf.pkl

4️⃣ Run the Application
```bash
python Spam.py
```

---

📸 Application Output

Displays SPAM (Probability%) in red

Displays HAM (Probability%) in green

Shows model loading status

---

🎯 Learning Outcomes

This project demonstrates:

Practical implementation of Natural Language Processing

Training & loading ML models

Real-world spam filtering logic

GUI development using Tkinter

Clean separation between model logic and interface

---

📌 Future Improvements

Add model training module inside the app

Add dataset upload feature

Improve preprocessing with stemming/lemmatization

Add dark/light theme toggle

Convert to web version using Flask or FastAPI


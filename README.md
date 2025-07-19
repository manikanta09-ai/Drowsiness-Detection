
# 🛑 Drowsiness Detection System

A real-time Drowsiness Detection System using computer vision techniques. This Python project detects if a person is drowsy based on eye aspect ratio (EAR) and alerts the user with a sound or warning on screen. Developed by [Manikanta Nallamalli](https://github.com/manikanta09-ai).

---

## 📌 Features

- Real-time webcam feed analysis
- Eye aspect ratio (EAR)–based blink detection
- Alerts driver or user during drowsiness
- Lightweight and fast processing

---

## 🧠 Tech Stack

- Python 3.x  
- OpenCV  
- playsound (for alert)

---

## 📂 Project Structure

```

Drowsiness-Detection/
├── drowsiness\_detection.py       # Main script
├── shape\_predictor\_68\_face\_landmarks.dat  # Pre-trained model (not in repo due to size)
├── requirements.txt              # Dependency list
└── README.md                     # Project documentation

````

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/manikanta09-ai/Drowsiness-Detection.git
cd Drowsiness-Detection
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download the shape predictor

Download `shape_predictor_68_face_landmarks.dat` from:
🔗 [https://github.com/davisking/dlib-models](https://github.com/davisking/dlib-models)

Place it in the project directory.

---

## ▶️ How to Run

```bash
drowsiness_detection.py
```

Make sure your webcam is enabled.

---

## ⚠️ How It Works

* Calculates Eye Aspect Ratio (EAR) using facial landmarks.
* EAR below a threshold (e.g., 0.25) for a few frames = drowsiness.
* Triggers an alarm when drowsiness is detected continuously.

---

## 📸 Sample Output

> ✅ Face detected
> 😴 Drowsiness alert triggered if eyes are closed for long
> 📢 Optional sound played via `playsound` module

---

## 👤 Author

**Manikanta Nallamalli**

* GitHub: [@manikanta09-ai](https://github.com/manikanta09-ai)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---


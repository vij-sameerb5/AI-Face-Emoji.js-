# EmotiFaceAI 😄😠😲

**Version 2.0**  
Real-time facial emotion detection in your browser using AI and emojis.

[🔗 Live Demo](https://github.com/vij-sameerb5)

---

## 📌 About the Project

**EmotiFaceAI** is a web-based application that detects your facial expressions in real-time and matches them with corresponding emojis. Built using **ReactJS** and **face-api.js** (powered by TensorFlow.js), it runs entirely in your browser — **no recordings, no data uploads, 100% privacy**.

### 🎯 Features

- Real-time face detection & emotion recognition
- Matches expressions with emojis
- Dynamically changes background color based on emotion
- Runs locally in your browser using WebRTC
- Lightweight, responsive UI

---

## 🧠 How It Works

Once your camera is enabled, the app will:

1. Detect your face using `face-api.js`
2. Recognize your facial expression
3. Replace the default emoji with a matching one
4. Change the background color based on the detected emotion

**Example:**

- 😀 Smiling → Laughing emoji, green background  
- 😠 Angry → Angry emoji, red background  
- 😐 Neutral → Straight face, gray background  

> ⚠️ _No images or data are stored or transmitted — everything happens locally in your browser._

---

## 😎 Supported Emotions

| Expression  | Emoji  |
|-------------|--------|
| Neutral     | 😐     |
| Happy       | 😀     |
| Sad         | 😥     |
| Angry       | 😠     |
| Fearful     | 😨     |
| Disgusted   | 🤢     |
| Surprised   | 😲     |

---

## 🧪 Demo

![Happy Demo](demo-images/happy.png)
![Angry Demo](demo-images/angry.png)
![Neutral Demo](demo-images/neutral.png)

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm or yarn
- A webcam-enabled device

### Installation

```bash
git clone https://github.com/louiejancevski/FacialEmotionDetector.git
cd FacialEmotionDetector
npm install

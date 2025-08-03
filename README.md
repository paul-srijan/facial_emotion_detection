
# Real-Time Emotion Detection with DeepFace and OpenCV

This project uses a webcam feed to detect human faces in real-time and analyze their emotions using the [DeepFace](https://github.com/serengil/deepface) library. It utilizes OpenCV for face detection and live video streaming.

## 🔍 Features

* Real-time face detection using Haar cascades.
* Emotion recognition using DeepFace (`emotion` action).
* Displays bounding boxes and predicted emotions on the video stream.
* Easy to run and extend for further facial analysis (age, gender, race, etc.).

---

## 🖼️ Demo

![Emotion Detection Demo](https://github.com/yourusername/emotion-detector/blob/main/demo.gif)
*Replace with your actual demo if available*

---

## 🧠 Tech Stack

* Python 3.x
* OpenCV
* DeepFace
* Haar Cascade Classifier (for face detection)

---

## ⚙️ Installation

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/emotion-detector.git
cd emotion-detector
```

2. **Create a Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

3. **Install Required Libraries**

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt`, install manually:

```bash
pip install opencv-python deepface
```

---

## ▶️ Usage

Run the following command:

```bash
python emotion_detection.py
```

> Press `q` to quit the video stream.

---

## 📁 File Structure

```
emotion-detector/
│
├── emotion_detection.py       # Main Python script
├── README.md                  # Project README
└── requirements.txt           # Python dependencies (optional)
```

---

## 📦 Optional `requirements.txt`

```
opencv-python
deepface
```

---

## 📝 Notes

* This script uses `haarcascade_frontalface_default.xml` from OpenCV’s pre-trained models.
* DeepFace downloads models (VGG-Face, Emotion model, etc.) on the first run — ensure internet access.
* For better performance, GPU acceleration is recommended.

---

## 📌 Future Improvements

* Add support for age/gender/race detection.
* Store detected emotions with timestamps for analysis.
* Improve face detection with DNN or MTCNN.
* Add GUI using Tkinter or PyQt.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


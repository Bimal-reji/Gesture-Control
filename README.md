# ✋ Gesture Control System

Control your computer with hand gestures using OpenCV, MediaPipe, and PyAutoGUI. This app uses webcam input to allow mouse and keyboard interaction through gestures.

## 📌 Features

- **Right Hand**:
  - 🖱️ Move mouse (all fingers open)
  - 👆 Left click (index + middle up)
  - 👉 Right click (index up only)
- **Left Hand**:
  - 🔼 Jump (thumb up)
  - ⬆️ Move Forward (all fingers up)
  - ⬅️ Move Left (middle up)
  - ➡️ Move Right (ring up)
  - ⬇️ Move Backward (pinky up)
  - ✊ Stop/Release all keys (fist)

## 🛠 Requirements

- Python 3.7+
- OpenCV
- MediaPipe
- PyAutoGUI
- Pillow (for GUI images)

Install all dependencies:

```bash
pip install -r requirements.txt

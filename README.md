# 🎮 Hand Gesture Keyboard Controller (MediaPipe)

A hands-free controller that translates specific hand gestures into **Left** ($\leftarrow$) and **Right** ($\rightarrow$) keyboard key presses using a webcam. This is ideal for controlling applications like simple racing games, character movement, or advancing slideshow presentations.



---

## 🔎 What It Is (Title and Description)
This project is a real-time computer vision application that creates a **Virtual Keyboard Controller**. It uses hand tracking to map hand postures directly to keyboard inputs, providing an alternative input method for interacting with desktop applications.

---

## ✨ What It Does (Features and Technologies)

### Features
* **Real-time Keyboard Control:** Simulates key presses for $\leftarrow$ and $\rightarrow$ based on hand gestures.
* **Dual Control:** Uses a **closed fist** for one action and an **open palm** for another.
* **Automatic Stop:** Keys are released when no hand is detected, ensuring safe disengagement.
* **Visual Feedback:** Displays hand landmarks and connections over the live camera feed.

### Technologies
* **Python:** Core programming language.
* **OpenCV (`cv2`):** Handles video capture and display.
* **MediaPipe (`mediapipe`):** Provides the high-performance hand detection and tracking framework.
* **pynput:** Manages virtual keyboard key presses and releases.

---

## 🛠️ How to Set It Up (Requirements/Installation)

### Prerequisites
* Python 3.x installed.
* A working webcam (built-in or external).

### Installation

1.  **Create `requirements.txt`** (if necessary):
    ```
    opencv-python
    mediapipe
    pynput
    ```
2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

---

## 🚀 How to Run It (.py)

Make sure your webcam is available and not in use by other applications.

Run the main script from your terminal:

```bash
python virtual_keyboard.py

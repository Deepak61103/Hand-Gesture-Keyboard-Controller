# 🎮 Hand Gesture Keyboard Controller (MediaPipe)

A hands-free controller that translates specific hand gestures into **Left** ($\leftarrow$) and **Right** ($\rightarrow$) keyboard key presses using a webcam. This is ideal for controlling applications like simple racing games, character movement, or advancing slideshow presentations.



---

## 🔎 Detailed Overview: Start-to-End Guide

### 1. What It Does
This program uses the **MediaPipe Hands** framework to detect and track a single hand in real-time. It monitors the state of your five fingers (open or closed) and uses that information to simulate keyboard presses using the `pynput` library.

### 2. Technologies
* **Python:** The core language.
* **OpenCV (`cv2`):** Used for capturing video from the webcam and displaying the output.
* **MediaPipe (`mediapipe`):** Provides the robust, high-performance hand detection and landmark tracking.
* **pynput:** Used to send virtual key press and release commands to the operating system.

---

## 🛠️ Installation and Setup

### Prerequisites

Ensure you have the following installed on your system:

* **Python 3.x**
* A working **webcam** (internal or external).

### Step 1: Get the Code

Clone the repository to your local machine using Git:

```bash
git clone [https://github.com/YourUsername/Hand-Keyboard-Controller.git](https://github.com/YourUsername/Hand-Keyboard-Controller.git)
cd Hand-Keyboard-Controller

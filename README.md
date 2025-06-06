# 🔫 Weapon Detection using OpenCV

This project is a simple yet powerful implementation of a real-time weapon (gun) detection system using Python, OpenCV, and a Haar cascade classifier. It captures video from your webcam and detects the presence of a gun in live video frames. 🛡️📹

## ✨ Features
- 📷 Real-time video stream analysis
- 🧠 Gun detection using Haar cascade (`cascade.xml`)
- 🔲 Visual feedback with bounding boxes
- 🔔 Terminal alert message if a weapon is detected

## 📦 Requirements
- Python 3.x 🐍
- OpenCV (`cv2`)
- imutils
- Haar cascade XML file for gun detection (`cascade.xml`)

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/byrohithreddy/Weapon_detection_system.git
   cd Weapon_detection_system
   ```

2. Install the dependencies:
   ```bash
   pip install opencv-python imutils
   ```

3. Ensure the `cascade.xml` file is present in the same directory as the script.

## 🚀 How to Run
```bash
python main.py
```
- Press `q` to exit the live video feed.

## 📤 Output
- 🟥 A bounding box will appear around any detected weapon in the feed.
- Terminal output:
  - `✅ gun detected` if a weapon was found
  - `❌ NO Weapon Detected` if none were found

## 🔍 Notes
- Detection accuracy depends on the quality and training of `cascade.xml`
- This is a **basic prototype** and may not be suitable for critical or production use
- For better performance, consider using deep learning models like **YOLO**, **SSD**, or **MobileNet**

## 📄 License
This project is licensed under the **MIT License**. Feel free to use and modify it for your own projects! 🧑‍💻

---
💡 *Contributions, stars ⭐, and feedback are always welcome!*


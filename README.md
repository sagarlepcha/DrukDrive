# DrukDrive
DrukDrive, also known as the Third Eye System, is an AI Vision Assistant designed for drivers in Bhutan. This innovative technology leverages advanced artificial intelligence and computer vision to detect and recognize traffic signs, enhancing road safety and driving efficiency. DrukDrive provides real-time alerts and notifications to drivers about upcoming traffic signs, ensuring they are well-informed and can react promptly to road conditions. This system is particularly beneficial in Bhutan's varied and often challenging driving environments, contributing to safer and more informed driving experiences.

## Features

- Real-time recognition of traffic signs.
- Instant alerts and notifications to drivers.
- Enhances road safety and driving efficiency.
- Especially useful for Bhutan’s challenging road environments.

---

## Repository Contents

This repository contains the following files and directories:

| File/Folder                         | Description |
|------------------------------------|-------------|
| `android_app/`                     | Source code for the Android app. |
| `DrukDrive_Promotional_Video.mp4` | A promotional video of the DrukDrive project. |
| `DrukDrive_poster.jpg`            | A poster/image summarizing the project. |
| `PRJ303_G9_Final_Documentation.pdf` | Final project documentation. |
| `.gitignore`                       | Git ignore configuration. |
| `README.md`                        | This file. |


## 🚀 Installation Guide

### Prerequisites
- Android Studio Flamingo 2022.2.1+
- Android SDK 33 (Tiramisu)
- Minimum Android API 26 (Android 8.0)

### Building from Source
1. Clone repository:
   ```bash
   git clone https://github.com/sagarllepcha/DrukDrive.git
   cd DrukDrive/android_app

2. Open project in Android Studio:

File > Open > Select android_app directory

Wait for Gradle sync to complete (≈5 mins)

3. Build APK:

bash: ./gradlew assembleDebug
Output: app/build/outputs/apk/debug/app-debug.apk

🛠 Technical Specifications
Component	Details
Detection Model	YOLOv5s (TensorFlow Lite optimized)
Inference Speed	23ms ±4ms (Pixel 6a)
Accuracy	94.2% mAP@0.5 (Bhutan Sign Dataset)
Target FPS	30 FPS (720p input)
App Size	82MB (ARM64 optimized)
📈 Future Roadmap
Dashcam integration for driver perspective analysis

Bhutanese voice assistant integration (Dzongkha)

Crowdsourced sign database maintenance

ADAS features (lane detection, collision warning)

🤝 Contribution Guidelines
Fork the repository

Create feature branch (git checkout -b feature/amazing-feature)

Commit changes (git commit -m 'Add amazing feature')

Push to branch (git push origin feature/amazing-feature)

Open Pull Request

📜 License
This project is proprietary software. All rights reserved. For licensing inquiries, please contact sagarlepcharobot@email.com.

📬 Contact
Project Lead: Sagar Lepcha
Research Group: PRJ303 Group 9
Affiliation: Royal Institute of Technology, Bhutan
Email: sagarlepcharobot@email.com

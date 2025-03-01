# MLKit-FER-System

## Overview
MLKit-FER-System is an Android-based Facial Emotion Recognition (FER) application that leverages **Google's ML Kit** and **TensorFlow Lite** to detect and classify human emotions in real-time. This project aims to provide an efficient and lightweight solution for mobile-based FER applications.

## Features
- **Real-time Emotion Detection** using TensorFlow Lite.
- **Facial Structure Analysis** with ML Kit.
- **Optimized for Mobile Devices** with minimal resource consumption.
- **Supports Multiple Emotions**: Happy, Sad, Angry, Neutral, etc.
- **Uses Pre-trained CNN Model** fine-tuned for mobile devices.
- **User-Friendly Interface** built using Android Studio.

## Tech Stack
- **Machine Learning:** TensorFlow Lite
- **Facial Recognition:** Google ML Kit
- **Programming Language:** Java/Kotlin
- **Platform:** Android

## Dataset
The model is trained on a hybrid dataset combining multiple well-known FER datasets:
- CK+ (Extended Cohn-Kanade)
- JAFFE (Japanese Female Facial Expression Database)
- FER2013 (Facial Expression Recognition 2013)
- RAF-DB (Real-world Affective Faces Database)

## Installation & Setup
### Prerequisites
- Android Studio installed
- Android device/emulator

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/MLKit-FER-System.git
   cd MLKit-FER-System
   ```
2. **Open in Android Studio**
3. **Sync and Build** the project.
4. **Run the App** on an emulator or physical device.

## Usage
1. Open the app and grant camera permissions.
2. Point the camera at a face.
3. The system detects facial features and classifies emotions.
4. View results in real-time on the screen.

## Performance
- **Model Accuracy:** ~83.2% on test dataset
- **Optimized for Mobile Devices** with TensorFlow Lite.

## Future Improvements
- Improved emotion detection accuracy using **advanced CNN architectures**.
- **Cross-platform compatibility** (iOS & Web versions).
- Adding support for **multimodal emotion detection** (voice, text, etc.).
- **Offline Processing Enhancements** to reduce latency.

---

**References:**
- [TensorFlow Lite](https://www.tensorflow.org/lite/)
- [Google ML Kit](https://developers.google.com/ml-kit)

# SeeTrafficSigns

An Android application for real-time traffic sign detection using computer vision and machine learning.

## Features

- **Real-time Detection**: Uses device camera to detect traffic signs in real-time
- **Speed Limit Recognition**: Identifies speed limit signs (30, 40, 50, 60, 70, 80, 100, 120 km/h)
- **OpenCV Integration**: Leverages OpenCV for image processing
- **TensorFlow Lite**: Uses machine learning model for sign classification

## Technology Stack

- **Android**: Java-based Android application
- **OpenCV**: Computer vision library for image processing
- **TensorFlow Lite**: Machine learning framework for on-device inference
- **Python**: Model training scripts (Jupyter notebooks)

## Project Structure

```
SeeTrafficSigns/
├── app/                    # Android application source code
├── OpenCV/                 # OpenCV library for Android
├── scripts/                # Python scripts for data processing and model training
│   ├── model_training/     # Jupyter notebook for training the model
│   ├── grayscale_converter.py
│   └── random_selector.py
└── gradle/                 # Gradle build configuration
```

## Requirements

- Android SDK (API 21+)
- Android Studio
- OpenCV for Android
- TensorFlow Lite

## Setup

1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle dependencies
4. Build and run on an Android device or emulator

## License

This project is licensed under the MIT License.

Copyright 2022 Solita Oy

See the source code for full license details.

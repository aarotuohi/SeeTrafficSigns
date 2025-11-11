# SeeTrafficSigns

A small Android app that detects and highlights traffic signs using a machine learning model and the device camera.

## What it does
- Streams camera input and identifies common traffic signs.
- Overlays detection results on the camera preview.
- Intended as a simple demo of mobile traffic-sign detection.

## Technologies used
- Android SDK — platform and APIs for the app.
- Kotlin — app implementation language.
- CameraX (or Camera2) — captures camera frames reliably.
- TensorFlow Lite — runs the traffic-sign model on-device.

## Quick start
1. Install Android Studio (and JDK 11+).
2. Clone the repo:
   git clone https://github.com/aarotuohi/SeeTrafficSigns.git
3. Open the project in Android Studio and build.
4. Run on a physical Android device (camera permission required).

## Development
- Open issues or pull requests for bugs, improvements, or model updates.
- Use feature branches and target the main branch for PRs.

## Notes
- Model and implementation details are in the project source — check the app module for classifiers and assets.
- See LICENSE (if present) for licensing details.

Maintainer: @aarotuohi

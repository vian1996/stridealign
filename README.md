# StrideAlign

**StrideAlign** is an AI-powered prosthetic and gait analysis app built using Streamlit. It allows clinicians and researchers to:
- Analyze live gait using a webcam or mobile phone camera
- Upload and compare pre-recorded gait videos
- Detect and visualize prosthetic joint motion
- Assess range of motion, symmetry, gait phases, and alignment
- Support bilateral and unilateral prosthetic users

## 💻 How to Run

1. Install Python (3.8–3.11 recommended)
2. Clone this repo and open the folder
3. Install required libraries:
   ```
   pip install -r requirements.txt
   ```
4. Launch the app:
   ```
   streamlit run stridealign_app.py
   ```

## 📦 Features
- Live camera or IP webcam input
- Full gait phase classification and alignment feedback
- Custom prosthetic visualization (unilateral/bilateral)
- Side-by-side video upload and comparison
- Auto-extracted joint data export (CSV)

## 📱 IP Camera Setup
Use apps like **IP Webcam (Android)** or **EpocCam (iOS)** to stream your phone's camera.

## 📜 License
This project is intended for educational and clinical prototyping only.

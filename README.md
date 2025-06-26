# 🌊 AquaSignature: Underwater Threat Detection using CRNN

- AquaSignature is a deep learning-powered system designed to recognize and classify underwater acoustic signals such as submarines, torpedoes, and marine animals. The core objective is to detect foreign underwater threats that cross a defined acoustic frequency barrier, making it highly relevant for naval defense and surveillance.

## 🎯 Main Objective
- To automatically detect and classify acoustic anomalies — such as submarines or torpedoes from other countries — based on their marine sound signatures. If the barrier of predefined frequency is crossed, the system raises an alert, helping defense forces monitor underwater activities in real time.

## 🔍 Use Case
- This project simulates a naval surveillance system that can:
- Distinguish between natural marine sounds (e.g., dolphins, ships)
- Identify suspicious patterns like torpedo or submarine movement
- Alert when sound frequency breaks the “safe zone” of underwater activity


## 🧠 Features
-  Processes .wav files containing marine acoustic data
- Extracts MFCC features and visualizes spectrograms
- Uses a CRNN (CNN + LSTM) architecture for spatial + temporal learning
- Detects when a frequency threshold is crossed
- Classifies sounds as torpedo, ship, dolphin, submarines etc.

## 🛠️ Technologies
- Python
- Librosa (audio feature extraction)
- TensorFlow/Keras (deep learning model)
- Scikit-learn (label processing)
- Matplotlib (visualization)
 
## 🔐 Real-World Applications
- Naval submarine detection systems
- Underwater mine or torpedo tracking
- Marine research and anomaly detection
- Coastal security monitoring



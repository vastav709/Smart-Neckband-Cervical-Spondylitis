
# 🏥 Smart Neckband for Cervical Spondylitis Detection & Monitoring

> **ML-based diagnostic system + IoT-enabled real-time posture monitoring**
> Tools: MATLAB · Machine Learning · IoT · ESP8266 · Blynk · Flex Sensors

---

## 📌 Project Overview

Cervical Spondylitis is a degenerative spine condition affecting millions.
Early detection and continuous monitoring are critical for effective treatment.

This project combines **Machine Learning-based clinical diagnosis** from MRI data
with an **IoT-enabled smart neckband** for real-time posture monitoring —
bridging the gap between clinical analytics and wearable healthcare technology.

---

## 🎯 Objectives

- Automate severity classification of Cervical Spondylitis from MRI-derived data
- Provide clinicians with an intuitive GUI for patient diagnosis
- Enable continuous real-time posture monitoring using wearable IoT sensors
- Alert patients when unsafe neck bending angles are detected

---

## 🧠 Machine Learning Module

### Dataset
- Patient MRI scan data — C2–C7 disc height measurements & vertebra angles
- Clinical parameters preprocessed into structured ML-ready format

### Methodology
| Step | Details |
|------|---------|
| Data Collection | Real-world patient MRI scan parameters |
| Preprocessing | Cleaning, normalisation, handling missing values |
| Feature Extraction | Biomechanical features from disc heights & angles |
| Model Training | SVM + Decision Tree classifier in MATLAB |
| Classification | Early · Moderate · Severe severity stages |
| Validation | Model performance validated across all severity stages |

### MATLAB GUI
- Patient data entry interface
- Automated model inference & prediction
- Visual diagnostic result display for clinicians
- Real-time severity stage output

---

## 📡 IoT Module — Smart Neckband

### Hardware Components
| Component | Purpose |
|-----------|---------|
| ESP8266 | Wi-Fi microcontroller for wireless data transmission |
| Flex Sensors | Detect neck bending angles in real time |
| Buzzer | Threshold-based alert for unsafe posture |
| Blynk Platform | Remote monitoring via mobile dashboard |

### How It Works
1. Flex sensors measure neck bending angles continuously
2. ESP8266 transmits data wirelessly to Blynk cloud
3. Mobile dashboard displays real-time posture data
4. Buzzer triggers alert when angle exceeds safe threshold

---

## 🛠️ Tech Stack

![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-ESP8266-orange?style=flat)
![Blynk](https://img.shields.io/badge/Blynk-00C89C?style=flat&logo=blynk&logoColor=white)
![ML](https://img.shields.io/badge/Machine%20Learning-SVM%20%2B%20Decision%20Tree-blue?style=flat)

**Domains:** Machine Learning · Healthcare Analytics · IoT Analytics ·
Predictive Modeling · Feature Engineering · Signal Processing ·
Data Preprocessing · Classification Models

---

## 📊 Key Results

- ✅ Successfully classified cervical spondylitis into 3 severity stages
- ✅ Real-time IoT posture monitoring with instant buzzer alerts
- ✅ Clinical GUI enabling non-technical users to operate the system
- ✅ End-to-end pipeline from raw MRI data to diagnostic output

---

## 📁 Project Structure

```
Smart-Neckband-Cervical-Spondylitis/
│
├── ML_Model/
│   ├── data_preprocessing.m
│   ├── feature_extraction.m
│   ├── classifier_training.m
│   └── gui_interface.m
│
├── IoT_Module/
│   ├── esp8266_code/
│   └── blynk_config/
│
└── README.md
```

---

## 👤 Author

**Anush Vastav**
B.Tech ECE · PES University, Bengaluru
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/vastavanush)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/vastav709)
  

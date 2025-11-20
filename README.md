# 🔥 Fire Detection System

::: {align="center"}
`<img src="https://via.placeholder.com/800x350/ff4500/ffffff?text=Fire+Detection+System" alt="Fire Detection Banner"/>`{=html}
:::

A simple Python application that uses **OpenCV Haar Cascades** to detect
fire from a webcam feed and play an alarm.

## 📸 Demo Preview

::: {align="center"}
`<img src="https://via.placeholder.com/600x350/000000/ffffff?text=Camera+Feed+Preview" alt="Camera Feed Preview"/>`{=html}
:::

## ✨ Features

-   🔥 Real-time fire detection\
-   🎥 Webcam live video processing\
-   🔊 Alarm sound playback\
-   🧠 Haar Cascade XML model\
-   🕹 Press **Q** to exit

## 📁 Project Structure

    main.py
    fire_detection.xml
    audio.mp3

## ⚙️ Installation

``` bash
git clone https://github.com/ocipk/fire-detection.git
cd fire-detection
pip install opencv-python playsound
```

## ▶️ Usage

``` bash
python main.py
```

## 📦 Requirements

-   Python 3.7+
-   opencv-python\
-   playsound

## 🔧 Configuration

``` python
fire = fire_cascade.detectMultiScale(frame, 1.2, 5)
```

## 🛠 Troubleshooting

  Issue                Fix
  -------------------- --------------------------------------------
  XML missing          Keep `fire_detection.xml` beside `main.py`
  Alarm not playing    Check audio file + playsound install
  Webcam not opening   Try `cv2.VideoCapture(1)`

## 👤 Contributors

-   You ❤️

## 📄 License

No license specified.

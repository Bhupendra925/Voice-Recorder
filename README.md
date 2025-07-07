# Voice-Recorder
This Python script records a short audio clip using the computer's microphone and saves it as .wav files in two different ways using two libraries: scipy and wavio.
By - BHUPENDRA KUMAR VISHWAKARMA || ENGINEER

# 🎙️ Audio Recorder in Python

This is a simple Python script to record audio using your microphone and save it as WAV files using two different libraries: `scipy.io.wavfile` and `wavio`.

---

## 📦 Requirements

Make sure you have the following Python libraries installed:


pip install sounddevice scipy wavio

## 🧪 How It Works
Records 5 seconds of audio using your system's microphone.

Saves the recording to two files:

recording0.wav using scipy.io.wavfile.write

recording1.wav using wavio.write

## 🚀 Usage
Just run the script:

bash
Copy
Edit
python audio_recorder.py

## 🛠️ Customization
You can change these parameters in the script:

python
Copy
Edit
duration = 5       # seconds
freq = 44100       # sample rate (Hz)
channels = 1       # mono (use 2 for stereo)

## 📜 License

This project uses the following open-source libraries:

Library	License
sounddevice	MIT
scipy	BSD-3-Clause
wavio	MIT


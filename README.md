# 🎙️ Speech Emotion Recognition using Machine Learning

An AI-powered audio analysis system that detects *human emotions from speech* and intelligently separates *non-speech sounds* like laughter, music, applause, and background noise.

This project uses *Machine Learning + Audio Signal Processing* to classify emotions and generate a *time-based emotion timeline* from uploaded audio.

---

## 🚀 Features

✅ Detects emotions from human speech
✅ Supports *audio upload (MP3/WAV)*
✅ Generates *emotion timeline visualization*
✅ Classifies *non-speech audio*:

* Laughter 😂
* Music 🎵
* Crowd / Noise 👏
* Speech 🎙️

✅ Displays *confidence score* for predictions
✅ Identifies *overall dominant emotion*
✅ Interactive notebook implementation in Google Colab

---

## 🧠 Emotions Detected

The model predicts the following emotions:

* Neutral 😐
* Calm 🙂
* Happy 😄
* Sad 😢
* Angry 😠
* Fearful 😨
* Disgust 😖
* Surprised 😲

Additional audio classes:

* Laughter 😂
* Music 🎵
* Crowd / Noise 👏

---

## 📂 Dataset Used

*RAVDESS*

* 24 actors
* 8 emotional states
* ~1500 speech recordings
* High-quality labeled audio dataset for Speech Emotion Recognition

---

## ⚙️ Technologies Used

* Python
* NumPy
* Librosa
* Matplotlib
* Scikit-learn
* Random Forest Classifier
* Google Colab

---

## 🔍 Audio Features Extracted

The model extracts important speech features such as:

* *MFCC (Mel Frequency Cepstral Coefficients)*
* *Delta MFCC*
* *Chroma Features*
* *Mel Spectrogram*
* *Spectral Contrast*
* *Pitch Detection (pyin)*
* *Zero Crossing Rate*
* *Energy / RMS*

These features help the model understand tone, intensity, pitch variation, and vocal characteristics.

---

## 🛠️ Data Augmentation

To improve robustness, audio samples are augmented using:

* Noise Injection
* Pitch Shifting
* Time Stretching

This improves generalization on real-world audio.

---

## 🧩 Project Pipeline

Audio Upload
↓
Audio Chunking (3 sec windows)
↓
Audio Type Detection
↓
If Speech → Emotion Classification
If Non-Speech → Laughter / Music / Noise Detection
↓
Confidence Scoring
↓
Timeline Visualization
↓
Dominant Emotion Output

---

## 📈 Output Example

```text
00s → HAPPY (82.4%)
03s → HAPPY (78.1%)
06s → LAUGHTER (91.2%)
09s → CALM (74.5%)

Overall Dominant Emotion → HAPPY
```

Timeline graph:

* X-axis → Time
* Y-axis → Confidence
* Labels → Detected emotion/audio type

---

## 🎯 Applications

* Mental Health Monitoring
* Call Center Sentiment Analysis
* Virtual Assistants
* Human Computer Interaction
* Entertainment Analytics
* Voice-based Emotion AI

---

## 🚧 Limitations

* Trained mainly on acted speech dataset
* Real-world noisy speech can reduce accuracy
* Non-speech confidence uses heuristic scoring
* Multi-speaker audio remains challenging

---

## 🔮 Future Improvements

* CNN / LSTM based deep learning models
* Real-time microphone emotion detection
* Larger multilingual datasets
* Speaker identification + emotion tracking
* Deployment as Web App / API

---

## 👩‍💻 Authors 

* *Shuchi Sharma*
* *Varun R*
* *Satavisa Deka*
* *Rohit B Kamath*


*From the Dept. of Computer Science & Business Systems (CSBS)*

---

## ⭐ Project Highlights

*Machine Learning + Signal Processing + Real-world Audio Intelligence*

A practical AI project that goes beyond simple classification by understanding *what kind of audio is present before predicting emotion*.

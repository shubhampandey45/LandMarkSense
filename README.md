# 🗺️ Landmark Sense AI

**Landmark Sense AI** is an Android application that uses AI to recognize landmarks across Asia using the on-device TensorFlow Lite model. It is built using Jetpack Compose for a modern UI experience and optimized performance.

---

## ✨ Features

- 🔍 Real-time landmark recognition using device camera
- 🧠 Offline AI model inference using TensorFlow Lite
- 🎨 Modern UI with Jetpack Compose
- 🌐 Recognizes over 98,000 Asian landmarks
- 📍 Displays landmark name

---

## 🛠️ Technologies & Tools Used

### 📦 Jetpack Compose  
A modern toolkit for building native UI. Used to develop a clean, responsive, and declarative user interface.

### 🧠 TensorFlow Lite Integration  
Integrated a pre-trained TensorFlow Lite model (Landmarks Classifier Asia V1) for on-device landmark recognition. The model runs efficiently without requiring internet connectivity.

### 📷 CameraX  
Used CameraX for real-time image capture and analysis. It provides consistent behavior across different Android devices and works seamlessly with Jetpack Compose.

---

## 🧠 Model Details

This app utilizes the [Landmarks Classifier Asia V1](https://www.kaggle.com/models/google/landmarks/tfLite/classifier-asia-v1) from Kaggle, developed by Google:

- **Model Format**: `.tflite`
- **Size**: ~50MB
- **Input**: 321x321 image
- **Output**: Top-5 most probable landmark class names and confidence scores


---


## 🔮 Future Enhancements
- 🧭 **Support for Global Landmark Models**  
  Integrate other regional and global TensorFlow Lite landmark models (e.g., Europe, Americas) to expand recognition beyond Asia.

- 🖼️ **Image Upload & Analysis**  
  Enable users to analyze landmarks from photos selected from their gallery.

- 🧠 **Landmark Quiz Mode**  
  Introduce a fun quiz where users guess the landmark based on AI predictions or obscured images.
  
- 📚 **Landmark Details with Historical Insights**  
  Provide users with cultural, historical, or architectural information for each recognized site.

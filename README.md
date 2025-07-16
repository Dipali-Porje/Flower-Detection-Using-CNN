# 🌸 Flower Detection System using CNN with Tkinter GUI

This project is a **deep learning-based flower classification system** that detects the type of flower from an image using a **Convolutional Neural Network (CNN)** and provides a **user-friendly desktop interface built with Tkinter**.

---

## 🌼 Classes Detected

The system is trained to classify multiple types of flowers, such as:
- 🌻 Sunflower
- 🌹 Rose
- 🌼 Daisy
- 🌷 Tulip
- 🌺 Dandelion  

---

## 🧠 Model Overview

- Model Type: **Convolutional Neural Network (CNN)**
- Input Image Size: **(150 x 150)** or as required
- Framework: **TensorFlow / Keras**
- Output: Flower class name with confidence score

---

## 🖥️ Tkinter GUI Features

- 🖼 Upload flower image from local system
- 🤖 Predict flower type using trained CNN
- 📋 Display result in the window (class name + confidence)
- 🧽 Reset or select another image easily

---

## 📂 Project Structure

flower_detection/
├── flower_model.h5 # Trained CNN model
├── flower_prediction.py # Tkinter GUI application
├── prediction.ipynb


---

## 🚀 How to Run the App

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/flower-detection-tkinter.git
cd flower-detection-tkinter

### 2️⃣ Install Dependencies

pip install -r requirements.txt

### 🎯 Future Improvements

Add multiple image batch classification
Improve UI with advanced themes (e.g., ttkbootstrap)
Add support for webcam-based prediction

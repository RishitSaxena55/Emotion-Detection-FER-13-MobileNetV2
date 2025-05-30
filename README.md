# 😄 Emotion Detection Using MobileNetV2 on FER-2013 Dataset

This project builds and fine-tunes a **MobileNetV2** model for facial emotion recognition using the **FER-2013** dataset. The model is trained to classify emotions into 7 categories and is evaluated using accuracy and loss plots.

---

## 📌 Overview

- 📦 **Model:** MobileNetV2 (transfer learning)
- 🧠 **Task:** Facial Emotion Recognition
- 🖼️ **Dataset:** FER-2013 (Kaggle)
- 🧪 **Emotions Detected:** Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- 📈 **Metrics Tracked:** Accuracy, Loss, Confusion Matrix

---

## 📁 Project Structure

fer13-emotion-recognition/
├── data/
│   ├── train/
│   │   ├── angry/
│   │   │   ├── image_001.jpg
│   │   │   ├── image_002.jpg
│   │   │   └── ...
│   │   ├── disgust/
│   │   │   ├── image_001.jpg
│   │   │   └── ...
│   │   ├── fear/
│   │   │   ├── image_001.jpg
│   │   │   └── ...
│   │   ├── happy/
│   │   │   ├── image_001.jpg
│   │   │   └── ...
│   │   ├── neutral/
│   │   │   ├── image_001.jpg
│   │   │   └── ...
│   │   ├── sad/
│   │   │   ├── image_001.jpg
│   │   │   └── ...
│   │   └── surprise/
│   │       ├── image_001.jpg
│   │       └── ...
│   └── test/
│       ├── angry/
│       │   ├── image_001.jpg
│       │   └── ...
│       ├── disgust/
│       │   ├── image_001.jpg
│       │   └── ...
│       ├── fear/
│       │   ├── image_001.jpg
│       │   └── ...
│       ├── happy/
│       │   ├── image_001.jpg
│       │   └── ...
│       ├── neutral/
│       │   ├── image_001.jpg
│       │   └── ...
│       ├── sad/
│       │   ├── image_001.jpg
│       │   └── ...
│       └── surprise/
│           ├── image_001.jpg
│           └── ...          └── ...

---

## 🎯 Dataset

- **Name:** FER-2013  
- **Source:** [Kaggle FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)
- **Details:** 48x48 grayscale facial emotion images  
- **Classes:**  
  `['Angry', 'Disgust', 'Fear', 'Happy', 'Sad', 'Surprise', 'Neutral']`

---

## 🧠 Model Architecture

- **Base Model:** MobileNetV2 (with pretrained ImageNet weights)
- **Input Shape:** (160, 160, 3)
- **Training Approach:** Fine-tune top layers of MobileNetV2
- **Output Layer:** Dense layer with softmax activation for 7 classes

---

## 📊 Evaluation Metrics

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

---

## 📈 Sample Plots

Plots are automatically generated in the notebook:

- 📉 **Accuracy vs Epoch**
- 📉 **Loss vs Epoch**

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/RishitSaxena55/Emotion-Detection-FER 13-MobileNetV2.git
cd Emotion-Detection-FER 13-MobileNetV2

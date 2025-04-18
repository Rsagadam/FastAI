# FastAI

# 🌾 Paddy Leaf Disease Detection using CNN & FastAI (Thermal Imaging)

This project uses Convolutional Neural Networks (CNNs) with the FastAI framework to detect and classify various paddy leaf diseases from **thermal images**. It aims to assist farmers and agricultural researchers by enabling early diagnosis through image classification techniques.

## 🚀 Project Highlights

- 🔥 **Thermal Image-Based Detection**: Leveraged thermal images (FLIR E8 camera) for classification.
- 🧠 **CNN with FastAI**: Built and trained CNN models using FastAI’s high-level API for quick experimentation and improved accuracy.
- 🎯 **Accuracy Achieved**: 81% on the validation set after fine-tuning.
- 🧪 **Classes Detected**: 
  - Bacterial Leaf Blight (BLB)
  - Blast
  - Leaf Folder
  - Leaf Spot
  - Hispa
  - Healthy Leaves

> 📌 *Note: My undergraduate work focused on three disease classes — Blast, Blight, and Leaf Folder.*

## 📊 Performance Report

| Metric         | Value  |
|----------------|--------|
| Validation Accuracy | 81%    |
| Precision (avg) | 0.76   |
| Recall (avg)    | 0.82   |
| F1-Score (avg)  | 0.77   |

Sample Prediction:
Predicted: Leaf Folder
Actual: BLB
Loss: 8.26
Probability: 0.86


## 🖼️ Dataset

- Total Images: 636
- Format: Thermal Images
- Source: Collected using FLIR E8 Camera across regions of Tamil Nadu
- Sample Path: `Dataset/thermal images UL/Blast/Thermalimage10a.jpg`

## 📌 To Do

- ✅ Thermal image model completed and evaluated
- 🔜 **RGB Model Coming Soon**: Exploring RGB images with FastAI – updates expected next week!

## 📎 Related Work

- Research aligned with modern precision agriculture techniques
- Inspired by use cases in AI for pest detection and smart farming solutions

## 📷 Visuals

Refer to attached images and screenshots in this repo for training logs, confusion matrix, and class-wise performance.

---

## 🧠 Model Training Logs (FastAI)

| Epoch | Train Loss | Valid Loss | Accuracy |
|-------|------------|------------|----------|
| 0     | 1.77       | 1.58       | 47.2%    |
| 1     | 1.49       | 1.39       | 63.8%    |
| 2     | 1.22       | 1.13       | 70.0%    |
| 3     | 1.02       | 0.80       | 79.5%    |
| 4     | 0.87       | 0.72       | 81.1%    |

---

## 🤝 Let's Connect

I'm passionate about combining AI and agriculture to solve real-world problems.  
Feel free to check out my [LinkedIn](https://www.linkedin.com/) and connect if you're interested in collaboration!

---


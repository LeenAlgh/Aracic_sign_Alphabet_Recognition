# Arabic Sign Language Alphabet Recognition 🤟🇸🇦

A deep learning-based system for recognizing Arabic Sign Language alphabets using sequential models. This project explores the performance of LSTM and GRU models in classifying hand gestures from webcam-captured images.

---

## Project Overview

This system translates Arabic Sign Language **alphabet** into text by recognizing static hand gestures. The dataset was collected manually in real time and includes **400 images per class**, covering **all 28 Arabic letters + 1 for "لا" (no)**.

---

## 🧪 Models Used

We trained and compared the performance of:
- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Unit)**

Each model was trained on time-series features extracted from image sequences to enhance temporal pattern recognition in gesture data.

---

## 📂 Dataset

-  29 classes (28 Arabic letters + 1 for "لا" (no)
-  400 samples per class
-  Real-time data collection using webcam
-  Preprocessed into `.npy` format

## 🖼️ Sample Output
Prediction results:
![Lam_Letter](https://github.com/user-attachments/assets/3542ed15-2b59-4ecd-b8c2-d337eb137759)
![Non_letter](https://github.com/user-attachments/assets/faa78e62-b9a3-4f26-ac95-54082a24fc5c)

![Yaa_letter](https://github.com/user-attachments/assets/133777a1-d3ee-429d-8c4e-a13446909baa)


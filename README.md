# 📌 Multimodal Arabic Fake News & Image Forgery Detection System

## 🔹 Overview
This project implements a dual‑module system designed to detect misinformation in both **text** and **images**.  
The system includes two independent components:

- **Text Module (NLP):** Detecting fake news using LSTM, GRU, BiLSTM, and Arabic BERT.  
- **Image Module (Computer Vision):** Detecting manipulated or falsified images using CNN, ResNet, and ELA preprocessing.

Both modules operate separately, each focusing on a specific data type (text or image).

---

## 🔹 Project Structure
FakeNews-ImageForgery-Detection  
│  
├── notebooks/  
│   ├── fake_news_experiment_1.ipynb  
│   ├── fake_news_experiment_2_gru.ipynb  
│   ├── fake_news_text_classification.ipynb  
│   ├── image_forgery_cnn.ipynb  
│   ├── image_forgery_detection.ipynb  
│  
└── README.md

---

## 🔹 Team Work
This project was developed as a **three‑member student team**.  
All experiments, preprocessing steps, and model implementations were collaboratively executed across both the NLP and Computer Vision modules.

---

## 🔹 Modules Included

### 📝 1) Fake News Detection (NLP)
Experiments include:
- LSTM  
- GRU  
- BiLSTM  
- Arabic BERT  
- Text preprocessing  
- Word embeddings (Glove)

Files:
- fake_news_experiment_1.ipynb  
- fake_news_experiment_2_gru.ipynb  
- fake_news_text_classification.ipynb

---

### 🖼️ 2) Image Forgery Detection (CV)
Experiments include:
- CNN  
- ResNet  
- ELA (Error Level Analysis)  
- Image preprocessing  
- Classification of real vs forged images

Files:
- image_forgery_cnn.ipynb  
- image_forgery_detection.ipynb

---

## 🔹 Datasets Used
- **AFND** – Arabic Fake News Dataset  
- **CASIA v1.0 / v2.0** – Image forgery datasets  
- **Columbia DVMM** – Splicing dataset  



---

## 🔹 Training Environment
A significant portion of the training was performed on the **university server**, due to:

- Large dataset sizes  
- GPU‑intensive models (BERT, ResNet)  
- Faster training and reduced runtime  
- Stable environment for long experiments  
- Unified library versions ensuring reproducibility  

---

## 🔹 Key Results
- Arabic BERT achieved the highest accuracy in text classification.  
- ResNet models performed best in image forgery detection.  
- ELA preprocessing improved image classification accuracy.  

---

## 🔹 Future Work
- Combine text + image into a unified multimodal model.  
- Extend the system to detect video forgery.  
- Improve performance on dialectal Arabic text.  

---

## 🔹 Project Team
Developed by a **three‑member student team**  
Faculty of Informatics Engineering – Artificial Intelligence Department

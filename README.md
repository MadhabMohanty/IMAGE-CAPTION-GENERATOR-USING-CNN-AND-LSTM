# IMAGE-CAPTION-GENERATOR-USING-CNN-AND-LSTM
# 🖼️ Image Caption Generator using CNN and LSTM

An **AI-powered image captioning system** that automatically generates descriptive captions for images and converts them into speech.  
The model combines **DenseNet201 (CNN)** for image feature extraction, **LSTM** for language generation, and **gTTS** for voice output — making it accessible for visually impaired users.

---

## 📘 Project Overview

This project generates **natural language descriptions** of images and reads them aloud using a **Text-to-Speech (TTS)** engine.  
It leverages deep learning models that combine **computer vision** and **natural language processing (NLP)** techniques.

### 🔑 Key Features
- Extracts image features using **DenseNet201** CNN model  
- Generates meaningful captions using an **LSTM-based sequence model**  
- Converts generated captions to speech using **gTTS (Google Text-to-Speech)**  
- Provides **voice descriptions** for accessibility  
- Achieves **91.2% accuracy** with optimized performance

---

## 🧩 Problem Statement

With the massive growth of digital imagery, manual image annotation is time-consuming and inconsistent.  
This system aims to **automate image captioning** and make visual content **accessible for visually impaired users** through voice-based image descriptions.

---

## 🎯 Objectives

- Develop an AI-powered image captioning model using CNN and LSTM  
- Integrate **Text-to-Speech (TTS)** for voice output  
- Optimize performance and accuracy through fine-tuning and model comparison  
- Enhance accessibility and user experience  

---

## 🧠 Background & Related Work

| Model | Description | Limitations |
|--------|--------------|-------------|
| **VGG16** | Early CNN used for feature extraction | High computational cost and redundant filters |
| **ResNet50** | Deep CNN with residual connections | Feature redundancy and less efficient reuse of features |
| **DenseNet201 (Proposed)** | Uses dense connections between layers, improving feature reuse and gradient flow | More complex architecture but higher efficiency |

**DenseNet201** outperforms other CNNs with better accuracy, generalization, and efficiency on moderate datasets.

---

## ⚙️ Technologies Used

| Component | Technology |
|------------|-------------|
| **Programming Language** | Python |
| **Frameworks** | TensorFlow, Keras |
| **Pre-trained CNN** | DenseNet201 |
| **Dataset** | [Flickr8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k) |
| **Text-to-Speech Engine** | [Google Text-to-Speech (gTTS)](https://cloud.google.com/text-to-speech) |
| **Development Tools** | Google Colab, Kaggle, NumPy, Pandas, Matplotlib |

---

## 🔍 Workflow

1. **Image Input:** The user uploads an image  
2. **Feature Extraction:** DenseNet201 extracts visual features  
3. **Caption Generation:** LSTM processes features and generates a text caption  
4. **Voice Conversion:** gTTS converts the caption into audio  
5. **Output:** The caption is displayed and spoken aloud  

---

## 🧮 Model Architecture

- **CNN (DenseNet201):** Extracts deep visual features from images  
- **LSTM:** Generates sequential text descriptions based on extracted features  
- **Attention Mechanism:** Enhances focus on relevant image regions  
- **TTS Module:** Converts text captions into natural-sounding speech  

---

## 🚀 Implementation Phases

1. **Research & Requirement Analysis**  
   - Studied existing models and challenges in image captioning  
2. **Dataset Collection & Preprocessing**  
   - Used Flickr8k dataset, resized and tokenized images/captions  
3. **Model Development**  
   - Built CNN + LSTM hybrid model with attention  
4. **Testing & Optimization**  
   - Tuned hyperparameters for better accuracy  
5. **Integration of TTS**  
   - Added gTTS for real-time voice output  
6. **Deployment & UI Development**  
   - Developed a simple interactive UI for real-time use  

---

## 📊 Results and Analysis

| Model | Accuracy | Loss |
|--------|-----------|------|
| **VGG16 + LSTM** | 47.6% | 1.74 |
| **ResNet50 + LSTM** | 66.7% | 0.98 |
| **DenseNet201 + LSTM (Proposed)** | **91.2%** | **0.23** |

✅ The **DenseNet201 model** achieved the highest accuracy and lowest loss, demonstrating robust caption generation.

---

## 🗣️ UI and Deployment

- User uploads an image → Caption generated → Voice output played  
- Interface built for simplicity and accessibility  

---

## 🧭 Future Enhancements

- Integrate **attention mechanism** for more accurate captions  
- Add **multilingual support** for caption and voice generation  
- Use **transformer-based models** like CLIP or ViT for contextual understanding  
- Optimize for **real-time captioning** and faster response  
- Include **interactive voice Q&A** about the image  

---

## 👨‍💻 Contributors

**Group No. Z10**

| Name | Regd. No. |
|------|------------|
| Nigamananda Panda | 2141016090 |
| Ganesh Chandra Das | 2141004078 |
| Akashdeep Behera | 2141002072 |
| **Madhav Narayan Mohanty** | 2141013300 |

**Supervised by:**  
Dr. Rangaballav Pradhan  
Department of Computer Science & Engineering  
ITER, Siksha ‘O’ Anusandhan University, Bhubaneswar, Odisha  

---

## 📚 References

- [Flickr8k Dataset – Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)  
- [Google Cloud TTS API](https://cloud.google.com/text-to-speech)  
- [DenseNet Paper (Huang et al., 2017)](https://arxiv.org/abs/1608.06993)  
- [ResNet Paper (He et al., 2016)](https://arxiv.org/abs/1512.03385)  
- [VGG16 Paper (Simonyan & Zisserman, 2014)](https://arxiv.org/abs/1409.1556)

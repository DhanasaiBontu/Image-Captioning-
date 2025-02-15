# Image-Captioning using Visual Attention

## 📌 Overview  
This project implements a **neural image captioning model** using **visual attention**. The model takes an image as input and generates a descriptive caption by leveraging deep learning techniques.  
---


## ✨ Features  
- Uses a **CNN** (such as ResNet) as an **image encoder**  
- Implements an **LSTM-based decoder** with an **attention mechanism**  
- Trained on a dataset of **image-caption pairs**  
- Generates captions dynamically based on **visual attention**  

---


## ⚙️ Prerequisites  

### 📂 Software Requirements:  
- Python 3.x  
- PyTorch  
- torchvision  
- NumPy  
- Matplotlib  
- NLTK  
- PIL (Pillow)  

---


## 📊 Dataset
- The model is trained on an image-caption dataset (e.g., MS COCO, Flickr8k, or Flickr30k).
- Ensure the dataset is preprocessed (tokenized, padded, and transformed into tensors).

---


## 🏗️ Model Architecture
- Image Encoder : A CNN extracts visual features from the input image.
- Attention Mechanism : Allows the decoder to focus on relevant image regions while generating each word.
- LSTM Decoder : Predicts the next word based on previous words and attended image features.

---


## 🎯 Results
- The model outputs a sequence of words describing the image.
- Attention maps highlight important regions contributing to each word.

---


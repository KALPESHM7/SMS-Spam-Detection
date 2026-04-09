# 📩 SMS Spam Detection using Deep Learning & Transfer Learning

## 🚀 Overview
This project focuses on building an intelligent SMS spam detection system using multiple deep learning approaches. The goal is to classify messages as **Spam** or **Ham (legitimate)** using modern NLP techniques.

---

## 🎯 Objectives
- Clean and preprocess SMS text data
- Convert text into numerical representations
- Build and compare multiple deep learning models
- Evaluate models using key performance metrics
- Visualize results for better interpretation

---

## 🧠 Models Implemented

### 1️⃣ Dense Embedding Model
- Uses Embedding + GlobalAveragePooling
- Fast and simple baseline model

### 2️⃣ Bidirectional LSTM (BiLSTM)
- Captures sequential dependencies
- Understands context and word order

### 3️⃣ Transfer Learning (Universal Sentence Encoder - USE)
- Uses pre-trained embeddings from TensorFlow Hub
- Best performing model with semantic understanding

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

---

## 📈 Visualizations
- Bar Chart (model comparison)
- Line Graph (performance trends)
- Confusion Matrix (error analysis)
- Heatmap (metric comparison)

---

## 🧪 Dataset
- SMS Spam Collection Dataset
- Contains labeled SMS messages (spam/ham)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/sms-spam-detection.git
cd sms-spam-detection

2️⃣ Install dependencies:
pip install -r requirements.txt
3️⃣ Run the notebook
jupyter notebook
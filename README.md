# Lightweight Edge-AI Framework for Real-Time Stress Detection and Adaptive Intervention

## 📌 Overview

This repository presents a lightweight Edge-AI framework for real-time stress detection and adaptive mental wellness support, designed for deployment on resource-constrained consumer electronics devices.

The proposed system integrates:
- Hybrid feature representation (TF-IDF + SVD + TinyBERT embeddings)
- Quantized transformer-based inference (FP16 and INT8)
- Real-time edge deployment using TensorFlow Lite
- Adaptive stress support agent for personalized intervention

The framework is validated on a Raspberry Pi platform, demonstrating low-latency, efficient, and scalable stress monitoring.

---

## 🚀 Key Contributions

- ✅ Hybrid feature fusion combining lexical and contextual representations  
- ✅ Lightweight TinyBERT-based stress classification  
- ✅ Edge optimization using FP16 and INT8 quantization  
- ✅ Real-time deployment on Raspberry Pi (Edge-AI setup)  
- ✅ Adaptive stress support agent for severity-based intervention  
- ✅ Comprehensive evaluation including latency, throughput, CPU, and memory metrics  

---

## 📊 Performance Summary

| Metric | Value |
|-------|------|
| Accuracy | 93.03% |
| ROC-AUC | 0.983 |
| INT8 Latency | 27.52 ms |
| Throughput | 36.35 samples/sec |
| CPU Usage | ~23.5% |
| Memory Usage | ~142 MB |

INT8 quantization achieves a strong balance between computational efficiency and predictive performance, making it suitable for real-time edge deployment.

---

## 🧠 System Architecture

The proposed system consists of:

1. **Offline Training Pipeline**
   - Text preprocessing
   - TF-IDF + SVD feature extraction
   - TinyBERT embedding extraction
   - Feature fusion and model training

2. **Edge Optimization**
   - Model conversion to TensorFlow Lite
   - FP16 and INT8 quantization

3. **Real-Time Inference**
   - On-device preprocessing
   - Stress probability prediction
   - Adaptive intervention generation

---

## ⚙️ Edge Deployment Setup

**Hardware:**
- Raspberry Pi 4 / Raspberry Pi 5  
- 2 GB RAM  

**Software:**
- Python 3.x  
- TensorFlow Lite Runtime  
- NumPy, Scikit-learn  
- Transformers (for tokenizer)

---


---

## 🧪 Sample Inference Workflow

1. Input text is preprocessed  
2. Features extracted (TF-IDF + TinyBERT)  
3. Model inference using TFLite  
4. Stress probability computed  
5. Adaptive agent generates response  

---

## 🤖 Adaptive Stress Agent

The system includes a context-aware adaptive agent:

| Stress Level | Intervention |
|-------------|-------------|
| Low | Maintenance Agent |
| Moderate | Grounding Agent |
| High | Cognitive Support Agent |
| Critical | Crisis Support Agent |

The decision is based on:
- Model probability
- Contextual linguistic indicators
- Crisis keywords (override mechanism)

---

## 📈 Experimental Results

- Strong classification performance (AUC = 0.983)  
- INT8 model achieves:
  - Lower latency  
  - Higher throughput  
  - Reduced memory and CPU usage  
- Distribution analysis shows:
  - INT8 → stable and deterministic  
  - FP16 → higher variance  

---



---

## 🔗 Dataset

- Mental Health Corpus (Kaggle)
Database: https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus?resource=download 
---




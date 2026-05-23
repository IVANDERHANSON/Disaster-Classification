# 🌍 Disaster Classification From Twitter (X) Using IndoBERT & BiLSTM

# 📂 Dataset

📥 Source:  
https://data.mendeley.com/datasets/r76v5sjyv2/2

📊 Total Data:
- 47,980 tweets

🏷 Labels:
| Label | Category |
|------|-----------|
| 0 | Fire |
| 1 | Flood |
| 2 | Earthquake |

---

# 🛠 Tech Stack

- Python
- PyTorch
- TensorFlow / Keras
- HuggingFace Transformers
- FastText
- Scikit-learn

⚡ Hardware:
- NVIDIA Tesla T4 GPU
- CUDA Enabled

---

# 🧹 Preprocessing

- Lowercase conversion
- URL removal
- Symbol cleaning
- Tokenization
- Whitespace removal

---

# 🧠 Models

## 🟣 IndoBERT
```text
Text → Tokenizer → Transformer → Classification
```

## 🔵 BiLSTM + FastText
```text
Text → FastText → BiLSTM → Softmax
```

---

# 📈 Results

✅ IndoBERT
- Accuracy: ~100%
- Best semantic understanding

✅ BiLSTM + FastText
- Validation Accuracy: >99%
- Faster & lightweight

---

# 📊 Evaluation

Metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

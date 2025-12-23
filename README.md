# 🇧🇩 Bangla Sarcasm & Sentiment Detection with Emojis 😄😡

## 📌 Overview
এই প্রজেক্টে বাংলা টেক্সটে **sarcasm এবং sentiment detection** করা হয়েছে, যেখানে **emoji-aware NLP** পদ্ধতি ব্যবহার করা হয়েছে।  
বাংলা ভাষার ক্ষেত্রে emoji প্রায়ই sentiment বা sarcasm বোঝাতে গুরুত্বপূর্ণ ভূমিকা রাখে—এই প্রজেক্টে সেটাকেই কাজে লাগানো হয়েছে।

The goal was to build an NLP pipeline that better understands **real-world Bangla social media text**, especially informal language mixed with emojis.

---

## 🧠 Problem Statement
Traditional Bangla NLP models often:
- Emojis ignore করে ❌  
- Sarcasm ভুলভাবে classify করে ❌  
- Informal Bangla (Facebook / comments) handle করতে পারে না ❌  

এই প্রজেক্টে এসব limitation address করার চেষ্টা করা হয়েছে।

---

## 🔍 Key Features
- 📝 Bangla text preprocessing (normalization, cleaning)
- 😀 Emoji extraction & encoding as features
- 🧠 Sarcasm & sentiment classification
- 📊 Comparative analysis: with vs without emoji features
- 📉 Error analysis on sarcastic samples

---

## ⚙️ Techniques Used
- Tokenization & text normalization (Bangla-focused)
- Emoji-to-sentiment mapping
- TF-IDF / embedding-based features
- Classical ML & deep learning models
- Train–validation performance comparison

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- PyTorch / TensorFlow (if used)
- NLTK / custom Bangla preprocessing
- Emoji library

---

## 📈 Results & Observations
- Emoji-aware models showed **better sarcasm detection**
- Improved classification on informal Bangla text
- Reduced false positives in sentiment prediction
- Emojis contributed meaningful semantic signals, especially in sarcastic contexts

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
python train.py
```

Or run the notebook:

jupyter notebook

🧪 Dataset Notes

Dataset contains Bangla text with emojis

Focused on social media–style language

Preprocessed for noise and informal spelling

(Dataset is excluded / partially included due to size or privacy constraints)

🎓 Academic Context

This project was developed as part of undergraduate NLP coursework and later extended to explore emoji-aware Bangla language modeling.

📬 Contact

Ahnaf Samin
Interested in NLP, AI/ML, and data-driven systems
📎 LinkedIn: (add link)


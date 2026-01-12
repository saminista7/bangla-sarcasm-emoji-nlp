# 🇧🇩 Bangla Sarcasm & Sentiment Detection with Emojis 😄😡

## 📌 Overview
This project focuses on **sarcasm and sentiment detection in Bangla text** using an **emoji-aware NLP pipeline**.  
Emojis play a crucial role in expressing sentiment and sarcasm in Bangla social media content, and this work explicitly models that signal instead of ignoring it.

The goal is to improve understanding of **real-world Bangla social media text**, especially informal language mixed with emojis.

---

## 🧠 Problem Statement
Most traditional Bangla NLP models struggle because they:
- Ignore emojis ❌
- Misclassify sarcastic content ❌
- Perform poorly on informal Bangla (Facebook posts, comments) ❌  

This project addresses these limitations by incorporating emoji-based features into the modeling pipeline.

---

## 🔍 Key Features
- 📝 Bangla text preprocessing (normalization, cleaning)
- 😀 Emoji extraction and encoding as features
- 🧠 Sarcasm and sentiment classification
- 📊 Comparative analysis (with vs without emoji features)
- 📉 Error analysis focused on sarcastic samples

---

## ⚙️ Techniques Used
- Bangla-focused tokenization and normalization
- Emoji-to-sentiment feature mapping
- TF-IDF / embedding-based representations
- Classical ML and deep learning models
- Train–validation performance comparison

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- PyTorch / TensorFlow
- NLTK and custom Bangla preprocessing
- Emoji library

---

## 📈 Results & Observations
- Emoji-aware models showed **improved sarcasm detection**
- Better performance on informal Bangla text
- Reduced false positives in sentiment classification
- Emojis provided meaningful semantic signals, especially in sarcastic contexts

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
python train.py
```
Or run the notebook:
jupyter notebook

📂 Dataset

The dataset used in this project is publicly available on Mendeley Data:

🔗 https://data.mendeley.com/datasets/7ryvn5gw88/2

Due to size and licensing considerations, the dataset is not included in this repository.


🇧🇩 বাংলা সংক্ষিপ্ত বিবরণ

এই প্রজেক্টে বাংলা টেক্সটে sarcasm এবং sentiment detection করা হয়েছে, যেখানে emoji-aware NLP পদ্ধতি ব্যবহার করা হয়েছে।
বাংলা সামাজিক যোগাযোগমাধ্যমে emoji প্রায়ই sarcasm ও sentiment বোঝাতে গুরুত্বপূর্ণ ভূমিকা রাখে—এই প্রজেক্টে সেটিকে কার্যকর feature হিসেবে ব্যবহার করা হয়েছে।

🎓 Academic Context

This project was developed as part of undergraduate NLP thesis coursework and later extended to explore emoji-aware Bangla language modeling.


📬 Contact
---
Ahnaf Samin
ahnaf.samin7@gmail.com
Interested in NLP, AI/ML, and data-driven systems

📎 LinkedIn: [(ahnafsamin7)](https://www.linkedin.com/in/ahnafsamin7)


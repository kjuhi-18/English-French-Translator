![banner](./project_banner_eng_fre.png)

# 🌍 English–French Transformer Translator  

**Neural Machine Translation with TensorFlow — an end-to-end pipeline for building, training & testing a Transformer model.**

---

## 🚀 Overview
This project builds a **Transformer-based sequence-to-sequence model** for **English → French translation**.  
It demonstrates the complete workflow:  
- Data ingestion & preprocessing  
- Custom tokenizer & vectorizer  
- Transformer encoder–decoder architecture  
- Training with masked loss & accuracy  
- Evaluation with real translation examples  
- Visualizations of training performance  

---

## ✨ Features
- 🧩 **Single Jupyter notebook** — easy to run and explore (`eng_fre.ipynb`)  
- 🔄 **Custom self-attention & cross-attention layers**  
- 📊 **Training visualization**: loss curves, accuracy, and translation samples  
- 🎯 Ready-to-use `translate()` function for quick inference  
- ⚡ Built with **TensorFlow**  

---

## 🛠️ Getting Started

### 1️⃣ Clone the repo
git clone https://github.com/kjuhi-18/English-French-Translator.git
cd English-French-Translator
2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the notebook
jupyter notebook eng_fre.ipynb


Or convert to script:

jupyter nbconvert --to script eng_fre.ipynb
python eng_fre.py

📁 Repository Structure
repo/
├─ eng_fre.ipynb        # main notebook
├─ README.md            # project documentation
├─ LICENSE              # license file
└─ requirements.txt     # dependencies

📦 Requirements

The project uses:

TensorFlow

NumPy

Matplotlib

Pathlib

Pickle

re, random, unicodedata (standard libs)

Install all with:

pip install -r requirements.txt


❤️ Contribute

Pull requests are welcome! If you have ideas for improvements (e.g., adding BLEU score evaluation, multilingual support, or attention visualizations), feel free to open an issue or PR.

📜 License

This project is licensed under the terms of the MIT License
.

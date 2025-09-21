![banner](./project_banner.png)

# 🌍 English–French Transformer Translator  

**Neural Machine Translation with TensorFlow — an end-to-end pipeline for building, training & testing a Transformer model.**

---

## 🚀 Overview
This project implements a **Transformer-based sequence-to-sequence model** for **English → French translation**.  
It demonstrates the **complete workflow**:  
- Data ingestion & preprocessing  
- Custom tokenizer & vectorizer  
- Transformer encoder–decoder architecture  
- Training with masked loss & accuracy  
- Evaluation with real translation examples  
- Visualizations of training performance  

---

## ✨ Highlights
- 🧩 **End-to-end notebook** — clean steps for data processing, model building, and evaluation  
- 📊 **Visualization outputs** (loss curves, accuracy metrics, translation examples)  
- 🔄 **Custom attention layers**: self-attention & cross-attention  
- ⚡ Built with **TensorFlow** for scalability  
- 🎯 Ready-to-use `translate()` function for inference  

---

## 🔎 Auto-detected Details
- 📒 Notebook file: `eng_fre_modified (3).ipynb`  
- 💻 Total cells: **56** (code: **56**, markdown: **0**)  
- 📦 Detected imports: `matplotlib, numpy, pathlib, pickle, random, re, tensorflow, unicodedata`  
- 🗂️ Data files referenced: `text_pair.pickle, vectorizer.pickle`  
- 🛠️ Functions defined:  
  `__call__, __init__, call, compute_mask, cross_attention, decoder, encoder, feed_forward, format_dataset, get_config, make_dataset, masked_accuracy, masked_loss, normalize, pos_enc_matrix, self_attention, transformer, translate`  
- 🖼️ Embedded output images extracted: **6** (see `notebook_images/`)  

---

## 🖼️ Visual Samples
Some plots & outputs generated during training:

![sample](./notebook_images/nb_output_cell32_out0.png)  
![sample](./notebook_images/nb_output_cell35_out0.png)  
![sample](./notebook_images/nb_output_cell38_out0.png)  
![sample](./notebook_images/nb_output_cell40_out0.png)  
![sample](./notebook_images/nb_output_cell42_out0.png)  
![sample](./notebook_images/nb_output_cell46_out1.png)  

---

## 🛠️ How to Run

**Option A — Run the notebook (recommended):**
```bash
pip install -r requirements.txt
jupyter notebook "eng_fre_modified (3).ipynb"

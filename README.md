# 📌 Bilingual Image Captioning (IEEE CONIT 2025)

**Conference:** 2025 5th International Conference on Intelligent Technologies (CONIT)  
**Publisher:** IEEE  
**DOI:** 10.1109/CONIT65521.2025.11167275  

---

## 📖 Overview

This project presents a bilingual image captioning system capable of generating captions in both **English and Malayalam**.

The architecture combines:

- 🖼 ResNet-18 CNN for visual feature extraction  
- 🤖 Transformer-based decoder inspired by Large Language Models (LLMs)  
- 🌐 Bilingual tokenizer with dynamic language control flag  
- 🔁 Autoregressive caption generation  

The model is trained on the **Malayalam Visual Genome 1.0 dataset**.

---

## 🧠 Model Architecture

- Encoder: ResNet-18  
- Decoder: Transformer (LLM-inspired)  
- Language Control Flag for inference  
- Separate tokenization for English and Malayalam  

---

## 📊 Evaluation Metrics

| Language   | BLEU  | METEOR | ROUGE-L |
|------------|-------|--------|---------|
| English    | 0.0456 | 0.2365 | 0.2317 |
| Malayalam  | 0.0233 | 0.2031 | 0.2883 |

---

## 🚀 Key Contributions

- Bilingual caption generation framework  
- LLM-inspired decoding strategy  
- Multimodal learning across low-resource language  
- Dynamic language selection during inference  

---

## 📄 Publication

🔗 IEEE Xplore Link:  
https://ieeexplore.ieee.org/document/11167275

---

## 🛠 Tech Stack

Python • PyTorch • CNN • Transformers • NLP • BLEU • METEOR • ROUGE

# 🧠 The WoI Encoder — My Way  
**Words of Importance: Semantic Transparency for AI**

> *"It’s not overfitting. It’s overperforming." – Johan Way™*

---

## 📁 Repository Structure

```
WoI/
├── data/
│   ├── wine_train_clean_v5.jsonl        # Cleaned & curated Kaggle wine dataset (truncated example)
│   ├── wine_is_fine.csv                 # Dataset used for WoI demonstration
│   ├── vocab_map.json                   # Token → index mapping (truncated)
│
├── output/
│   ├── quad_encoded_data_flat.json      # Example encoded data (hashed + information weights)
│   ├── woi_sweep_accuracy.png           # Accuracy plot for dynamic WoI sweep
│   ├── woi_sweep_accuracy.csv           # Results table (WoI vs accuracy)
│
├── examples/
│   └── Exclusive to business agreements and academic collaborations  
│       under signed NDA on my terms.
│
├── src/
│   └── Proprietary – core algorithms and methods are not included.  
│       Available only under research or licensing collaboration.
│
├── README.md
│
└── LICENSE  
    Exclusive to business agreements and academic collaborations  
    under signed NDA on my terms.
```

---

## 🌍 Overview

The **WoI Encoder (Words of Importance)** is a conceptual framework and experimental encoder designed to *measure the information value of words*.  
It unites **semantic transparency**, **mutual information weighting**, and **encryption-based tokenization** to show that *interpretability* and *compression* can coexist.

Built entirely on a **Mac M3 Air**, using standard Python tooling — a demonstration of how far individual innovation can go.

---

## ⚗️ Methodology

The encoder transforms text into numerical representations weighted by *Word-level Information (WoI)*.  
Each token is assigned a deterministic yet encrypted hash, allowing controlled reconstruction and mutual information (MI) evaluation.

The system:
- Encodes text via POS-aware hashing  
- Computes normalized MI weights  
- Aggregates signals into interpretable “WoI vectors”  
- Demonstrates classification efficiency with minimal compute requirements  

See [`docs/methodology.md`](docs/methodology.md) for a detailed conceptual description.

---

## 📊 Results

**Example Task:** *Wine Review Classification*  

**Dataset:** `wine_is_fine.csv`  
Curated subset derived from the open *Wine Reviews* dataset on Kaggle:  
🔗 https://www.kaggle.com/datasets/zynicide/wine-reviews

License: Public domain / Creative Commons Attribution (original source).  
Processed and normalized by **Johan Eskils** for semantic encoder benchmarking.

**Model:** Logistic Regression  
**Platform:** Mac M3 Air  

| WoI Threshold | Accuracy |
|---------------|-----------|
| 100 | 0.72 |
| 200 | 0.78 |
| **400** | **0.81** |
| 800 | 0.79 |

📈 *Figure:* `output/woi_sweep_accuracy.png`  

> “Not overfitting — overperforming.”  

---

## 🧠 Purpose

WoI represents an ongoing exploration into:
- Low-compute semantic modeling  
- Information-driven interpretability  
- Transparent encoding for AI governance and data security  

It reflects a vision where understanding meaning is measurable —  
and where every word counts.

---

## 🛡️ License

This repository is shared **for demonstration and research purposes only**.  
All source code related to the *core encoding mechanism* is **proprietary** and **not included**.  
Distribution or reuse is subject to signed NDA and collaboration agreement.

© 2025 **Johan Eskils** — All rights reserved.

---

## ✉️ Contact

For collaboration or research inquiries:  
🔗 [linkedin.com/in/johaneskils](https://www.linkedin.com/in/johaneskils)  
📧 *Email available upon request*

---

## 🧩 Citation

If referencing this work in research or media, please cite:

```
@misc{Eskils2025WoI,
  author = {Johan Eskils},
  title  = {The WoI Encoder — Words of Importance},
  year   = {2025},
  note   = {Pre-release concept, ongoing research}
}
```

---

> *“Sometimes it takes one person to redefine meaning itself.  
> And when LLMs finally speak my language… you’ll know.”*

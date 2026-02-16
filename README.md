# SGV-LowRes-NMT
**Official Implementation of "Structure-Guided Generation and Verification (SGV) for Low-Resource NMT"**

This repository contains the code for the SGV framework, designed to construct high-quality parallel corpora for low-resource agglutinative languages (Uzbek, Kazakh, Kyrgyz) aligned with Chinese.

## 🏗 Architecture
The system consists of three main pipelines:
1.  **Generator:** IGT-Augmented Prompting using LLMs (Qwen2.5).
2.  **Verifier:** Dynamic Dual-Encoder Fusion (LaBSE + LASER) with Cross-Attention.
3.  **Selector:** Adaptive Filtering using Margin-based Scoring.

## 🚀 Quick Start

### 1. Installation
```bash
git clone [https://github.com/yourusername/SGV-LowRes-NMT.git](https://github.com/yourusername/SGV-LowRes-NMT.git)
cd SGV-LowRes-NMT
pip install -r requirements.txt
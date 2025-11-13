## LLM Learning Roadmap 

Explore **Large Language Models** through hands-on Jupyter notebooks. From environment setup to fine-tuning BERT and using Hugging Face — all in one place.

---

## Learning Path Overview

| Stage | Focus | Key Tools & Models |
|------|-------|---------------------|
| 1️⃣ **Setup & Environment** | Colab, APIs, config | `transformers`, `datasets`, `accelerate` |
| 2️⃣ **Hugging Face Basics** | Pipelines, inference | Text generation, classification |
| 3️⃣ **BERT & Variants** | Tokenization, fine-tuning | BERT, RoBERTa, DistilBERT |
| 4️⃣ **XLNet & Advanced** | Permutation training | XLNet, T5, GPT-style models |

---

## Detailed Roadmap


<summary><strong>1. Setup & Environment</strong> – Get ready for LLM workflows</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`LLM01_setting_up_AI.ipynb`](LLM/LLM01_setting_up_AI.ipynb) | Install dependencies, configure GPU/Colab, API keys |
| 2 | [`config.py`](LLM/config.py) | Central config for paths, models, and credentials |




<summary><strong>2. Hugging Face Pipelines</strong> – Instant NLP with pre-trained models</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`LLM02_Hugging_face.ipynb`](LLM/LLM02_Hugging_face.ipynb) | Use `pipeline()` for sentiment, NER, summarization, generation |


<summary><strong>3. BERT & Fine-Tuning</strong> – Master the transformer backbone</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`LLM03_BERT.ipynb`](LLM/LLM03_BERT.ipynb) | Tokenize, fine-tune BERT on emotion classification |
| - | [`emotion-labels-train.csv`](LLM/emotion-labels-train.csv) | Training dataset |
| - | [`emotion-labels-val.csv`](LLM/emotion-labels-val.csv) | Validation dataset |
| - | [`emotion-labels-test.csv`](LLM/emotion-labels-test.csv) | Test dataset |


<summary><strong>4. XLNet & Advanced Architectures</strong> – Beyond BERT</summary>

| # | Notebook | Description |
|---|--------|-----------|
| 1 | [`LLM04_XLNET.ipynb`](LLM/LLM04_XLNET.ipynb) | Permutation language modeling, XLNet inference & fine-tuning |



---

## Datasets Included

| File | Purpose |
|------|--------|
| `emotion-labels-train.csv` | Labeled text for training emotion classifier |
| `emotion-labels-val.csv` | Validation split |
| `emotion-labels-test.csv` | Held-out test set |

> **Task**: Multi-class emotion detection (joy, anger, sadness, etc.)


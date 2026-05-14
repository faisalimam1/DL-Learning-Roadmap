# 🧠 AI/ML, DL Roadmap — Faisal Imam
### From Deep Learning Foundations → HuggingFace → LLMs & RAG → Deploy & Ship

![Progress](https://img.shields.io/badge/Progress-Day%2011%20of%2030-blue?style=for-the-badge)
![Phase](https://img.shields.io/badge/Current%20Phase-2%20HuggingFace%20%26%20Transformers-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Building%20in%20Public-brightgreen?style=for-the-badge)

> **Goal:** Go from fundamentals to 4 deployed AI projects.
> **Rule:** One commit every day. No exceptions.

---

## 🗺️ Roadmap Overview

| Phase | Topic | Days | Status |
|-------|-------|------|--------|
| **Phase 1** | Deep Learning Foundations | Days 1–8 | ✅ Complete |
| **Phase 2** | HuggingFace & Transformers | Days 9–16 | 🔄 In Progress |
| **Phase 3** | LLMs, Prompt Engineering & RAG | Days 17–24 | ⏳ Upcoming |
| **Phase 4** | Deploy & Ship | Days 25–30 | ⏳ Upcoming |

---

## 📁 Repository Structure

```
DL-Learning-Roadmap/
│
├── 📓 phase-1-deep-learning.ipynb     ← Days 1–8 (Complete)
├── 📓 phase-2-huggingface/
│   └── Phase-2-DL-HuggingFace.ipynb  ← Days 9–16 (In Progress)
├── 📓 phase-3-llms-rag.ipynb          ← Days 17–23 (Coming Soon)
├── 📓 phase-4-deploy.ipynb            ← Days 25–30 (Coming Soon)
│
├── 🚀 Project 1: Image Classifier     ← Phase 1 capstone (Day 8) ✅
├── 🚀 Project 2: NLP Multi-Tool       ← Phase 2 capstone (Day 16)
├── 🚀 Project 3: RAG Chatbot          ← Phase 3 capstone (Day 24)
├── 🚀 Project 4: RAG API (Prod)       ← Phase 4 capstone (Day 30)
│
└── README.md
```

---

## 📅 Daily Progress Log

### ✅ Phase 1: Deep Learning Foundations — COMPLETE

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|---------|
| ✅ Day 1 | Neural Net from Scratch | NumPy · Forward Pass · Backprop | Loss: 0.25 → 0.000165 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 2 | Backprop & Gradient Descent | Chain Rule · MSE vs CE | CE gap 18x better | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 3 | PyTorch Crash Course | Tensors · Autograd · Adam vs SGD | Adam: 0.004 SGD: 0.690 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 4 | Training Loop + Regularization | Dropout · BatchNorm · Early Stop | Gap reduced 18x, stopped epoch 409 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 5 | CNNs — MNIST | Conv2D · MaxPool · Feature Maps | 98.99% test accuracy | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 6 | Transfer Learning | ResNet-18 · Fine-tuning | Frozen: 81.5% → Fine-tuned: 95.5% | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 7 | RNNs & LSTMs | LSTM Gates · Vanishing Gradient | 2 silent bugs found & fixed | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 8 | **PROJECT: Image Classifier** | Gradio · HuggingFace Spaces | Deployed — Live URL | [View](https://github.com/faisalimam1/plant-disease-classifier) |

---

### 🔄 Phase 2: HuggingFace & Transformers — In Progress

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|---------|
| ✅ Day 9 | Attention Mechanism | Self-Attention · Q/K/V · Positional Encoding | Built from scratch in NumPy — attention heatmap visualized | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 10 | HuggingFace Pipelines | pipeline() · Model Cards · NLI | 5 NLP tasks: Sentiment · NER · Summarization · QA · Zero-Shot | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 11 | Tokenizers Deep Dive | BPE · WordPiece · Attention Mask · Truncation | BPE vs WordPiece compared — emoji [UNK] bug · 23.6% silent truncation · Hindi character explosion | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ⏳ Day 12 | Fine-tuning BERT | Trainer API · AutoModel | — | Coming |
| ⏳ Day 13 | NLP Metrics | F1 · ROUGE · BLEU · Perplexity | — | Coming |
| ⏳ Day 14 | Sentence Transformers | Embeddings · Semantic Search | — | Coming |
| ⏳ Day 15 | LoRA & PEFT | Efficient Fine-tuning | — | Coming |
| ⏳ Day 16 | **PROJECT: NLP Multi-Tool** | Streamlit · HF Hub | — | Coming |

---

### Phase 3: LLMs & RAG

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|---------|
| ⏳ Day 17 | LLM APIs | OpenAI · Anthropic · Gemini | — | Coming |
| ⏳ Day 18 | Prompt Engineering | Zero-shot · Few-shot · CoT | — | Coming |
| ⏳ Day 19 | Vector Databases | FAISS · ChromaDB | — | Coming |
| ⏳ Day 20 | RAG Pipeline v1 | PDF → Chunk → Embed → LLM | — | Coming |
| ⏳ Day 21 | RAG Retrieval Quality | Chunking · Hybrid Search | — | Coming |
| ⏳ Day 22 | LangChain Basics | Chains · Memory · Tools | — | Coming |
| ⏳ Day 23 | AI Agents | Function Calling · ReAct Loop | — | Coming |
| ⏳ Day 24 | **PROJECT: RAG Chatbot** | ChromaDB · Gradio · HF Spaces | — | Coming |

---

### Phase 4: Deploy & Ship

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|---------|
| ⏳ Day 25 | FastAPI | REST API · Pydantic · Swagger | — | Coming |
| ⏳ Day 26 | Streamlit / Gradio UI | Demo GIF · Chat Interface | — | Coming |
| ⏳ Day 27 | Docker | Dockerfile · docker-compose | — | Coming |
| ⏳ Day 28 | Deploy to Render + HF Spaces | Live URL · Environment Vars | — | Coming |
| ⏳ Day 29 | GitHub Portfolio Cleanup | README · Badges · Pinned Repos | — | Coming |
| ⏳ Day 30 | Interview Prep | 30 Q&As · STAR Format | — | Coming |

---

## 🚀 Live Projects (Built During Roadmap)

| Project | Stack | Live Demo | Status |
|---------|-------|-----------|--------|
| 🖼️ Image Classifier | PyTorch · ResNet · Gradio | [View](https://github.com/faisalimam1/plant-disease-classifier) | ✅ Deployed |
| 🤗 NLP Multi-Tool | BERT · HuggingFace · Streamlit | Coming Day 16 | 🔄 Building |
| 🤖 RAG Chatbot | LangChain · ChromaDB · Gradio | Coming Day 24 | ⏳ |
| ⚙️ RAG API (Production) | FastAPI · Docker · Render | Coming Day 30 | ⏳ |

---

## 💡 Key Results So Far

### Phase 1 — Deep Learning
| Concept | What I Proved |
|---------|--------------|
| Neural Net from Scratch | Loss dropped 0.25 → 0.000165 in pure NumPy |
| Backpropagation | Chain rule verified manually — matched PyTorch autograd exactly |
| Adam vs SGD | Adam loss 0.004 vs SGD loss 0.690 on same problem |
| Regularization | Overfitting gap reduced 18x with Dropout + BatchNorm |
| CNN on MNIST | 98.99% test accuracy in 5 epochs |
| Transfer Learning | Fine-tuned ResNet 95.5% vs Frozen 81.5% vs Scratch 90.5% |
| Vanishing Gradient | RNN gradient steps 1-10: 0.000000 vs steps 90-100: 0.002065 |
| Silent Bugs Found | BCELoss saturation + imbalanced dataset — both caught and fixed |

### Phase 2 — HuggingFace & Transformers
| Concept | What I Proved |
|---------|--------------|
| Attention from Scratch | Built Q/K/V attention in pure NumPy — visualized heatmap for 3-token and 6-token sequences |
| Positional Encoding | Proved every position gets a unique sinusoidal fingerprint — no two rows identical |
| Sentiment Analysis | Neutral sentence ("okay, nothing special") → NEGATIVE 0.983 — exposed training data bias |
| NER | Detected PER/ORG/LOC entities — found model missed DATE class (not in CoNLL-03 label space) |
| Summarization | 116 words → 36 words (69% compression) with BART — identified first-paragraph bias |
| QA — Unanswerable | SQuAD2 model returned empty answer + 0.0000 confidence when answer not in context |
| Zero-Shot Classification | One MNLI model classified text into topic/urgency/department with no task-specific training |
| BPE vs WordPiece | BERT (30k vocab) vs GPT2 (50k vocab) — different split points on same words |
| Attention Mask | Batched 2 sentences — sentence 1 got 4 padding zeros, sentence 2 had none |
| Silent Truncation | 670 tokens truncated to 512 — 23.6% of data lost with zero warning |
| Edge Cases | Emojis → [UNK] · Hindi → character explosion (6 words = 17 tokens) · Numbers → no numeric understanding |

---

## 🛠️ Tech Stack (Built Up Over 30 Days)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)

---

## 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20My%20Journey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faisalimam19)
[![Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebooks-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/faisalimam19)
[![GitHub](https://img.shields.io/badge/GitHub-faisalimam1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/faisalimam1)

---

*Updated daily — every result in this README was actually measured, not estimated.*

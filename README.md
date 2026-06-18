# 🧠 AI/ML, DL Roadmap — Faisal Imam
### From Deep Learning Foundations → HuggingFace → LLMs & RAG → Deploy & Ship

![Progress](https://img.shields.io/badge/Progress-Day%2021%20of%2030-blue?style=for-the-badge)
![Phase](https://img.shields.io/badge/Current%20Phase-3%20LLMs%20%26%20RAG-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Building%20in%20Public-brightgreen?style=for-the-badge)

> **Goal:** Go from fundamentals to 4 deployed AI projects.
> **Rule:** One commit every day. No exceptions.

---

## 🗺️ Roadmap Overview

| Phase | Topic | Days | Status |
|-------|-------|------|--------|
| **Phase 1** | Deep Learning Foundations | Days 1–8 | ✅ Complete |
| **Phase 2** | HuggingFace & Transformers | Days 9–16 | ✅ Complete |
| **Phase 3** | LLMs, Prompt Engineering & RAG | Days 17–24 | 🔄 In Progress |
| **Phase 4** | Deploy & Ship | Days 25–30 | ⏳ Upcoming |

---

## 📁 Repository Structure

```
DL-Learning-Roadmap/
│
├── 📓 phase-1-deep-learning.ipynb          ← Days 1–8 (Complete)
├── 📓 phase-2-huggingface/
│   └── Phase-2-DL-HuggingFace.ipynb        ← Days 9–16 (Complete)
├── 📓 phase-3-LLMs-RAG/
│   └── Phase-3-LLMs-RAG.ipynb              ← Days 17–24 (In Progress)
├── 📓 phase-4-deploy.ipynb                 ← Days 25–30 (Coming Soon)
│
├── 🚀 Project 1: Image Classifier          ← Phase 1 capstone (Day 8)  ✅ Live
├── 🚀 Project 2: NLP Multi-Tool            ← Phase 2 capstone (Day 16) ✅ Live
├── 🚀 Project 3: RAG Chatbot               ← Phase 3 capstone (Day 24) ⏳
├── 🚀 Project 4: RAG API (Prod)            ← Phase 4 capstone (Day 30) ⏳
│
└── README.md
```

---

## 📅 Daily Progress Log

### ✅ Phase 1: Deep Learning Foundations — COMPLETE

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ✅ Day 1 | Neural Net from Scratch | NumPy · Forward Pass · Backprop | Loss: 0.25 → 0.000165 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 2 | Backprop & Gradient Descent | Chain Rule · MSE vs CE | CE gap 18x better | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 3 | PyTorch Crash Course | Tensors · Autograd · Adam vs SGD | Adam: 0.004 vs SGD: 0.690 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 4 | Training Loop + Regularization | Dropout · BatchNorm · Early Stop | Overfitting gap reduced 18x, stopped epoch 409 | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 5 | CNNs — MNIST | Conv2D · MaxPool · Feature Maps | 98.99% test accuracy | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 6 | Transfer Learning | ResNet-18 · Fine-tuning | Frozen: 81.5% → Fine-tuned: 95.5% | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 7 | RNNs & LSTMs | LSTM Gates · Vanishing Gradient | 2 silent bugs found & fixed | [View](./phase-1-deep-learning.ipynb) |
| ✅ Day 8 | **PROJECT: Image Classifier** | Gradio · HuggingFace Spaces | Deployed — Live URL | [View](https://github.com/faisalimam1/plant-disease-classifier) |

---

### ✅ Phase 2: HuggingFace & Transformers — COMPLETE

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ✅ Day 9 | Attention Mechanism | Self-Attention · Q/K/V · Positional Encoding | Built from scratch in NumPy — attention heatmap visualized | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 10 | HuggingFace Pipelines | pipeline() · Model Cards · NLI | 5 NLP tasks: Sentiment · NER · Summarization · QA · Zero-Shot | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 11 | Tokenizers Deep Dive | BPE · WordPiece · Attention Mask · Truncation | BPE vs WordPiece compared — emoji [UNK] · 23.6% silent truncation · Hindi character explosion | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 12 | Fine-tuning BERT | Trainer API · AutoModel · HF Hub | F1: 0.921 · Accuracy: 92% · Model live on HuggingFace Hub | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 13 | NLP Evaluation Metrics | F1 · ROUGE · BLEU · Perplexity | ROUGE-2 paradox: partial summary (0.381) beat good summary (0.351) | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 14 | Sentence Transformers | Embeddings · Cosine Similarity · Semantic Search | 8-line semantic search engine — king↔monarch=0.736, king↔bicycle=0.275 | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 15 | LoRA & PEFT | Efficient Fine-tuning · QLoRA | 0.65% trainable params (811k/125M) · 3.1MB adapter vs 475MB full model · 99.3% storage saving | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |
| ✅ Day 16 | **PROJECT: NLP Multi-Tool** | Streamlit · Fine-tuned BERT · HF Hub | Deployed — [nlp-multitool-app.streamlit.app](https://nlp-multitool-app.streamlit.app) | [View](./phase-2-huggingface/Phase-2-DL-HuggingFace.ipynb) |

---

### 🔄 Phase 3: LLMs & RAG — In Progress

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ✅ Day 17 | LLM APIs | Groq · Roles · Temperature · JSON Mode | Temperature experiment (0.0 / 0.7 / 1.5) · JSON extraction · domain Q&A bot with injection-resistant system prompt | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 18 | Prompt Engineering | Zero-shot · Few-shot · CoT · ReAct · Injection | Few-shot enforced exact format · CoT traced $9.00 step-by-step · ReAct reached 3.6M docs/day · V1 prompt failed injection, V2 held on all 3 attacks | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 19 | Vector Databases | FAISS · ChromaDB · Cosine Similarity · ANN | Proved meaning-based retrieval beats keyword search — "weight optimization algorithm" scored 0 keyword overlap but 0.460 semantic similarity on the correct chunk | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 20 | RAG Pipeline v1 | PDF → Chunk → Embed → ChromaDB → Grounded LLM | Built full RAG on India's Bharatiya Nyaya Sanhita (BNS) 2023 — caught an LLM confidently stating BNS "isn't in effect yet" (false) when asked without RAG; grounded version correctly refused instead | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 21 | RAG Retrieval Quality | Structure-Aware Chunking · BM25 · Hybrid Search · RRF | Found & fixed 2 layered bugs (hidden cross-reference table contamination, mid-sentence chunk truncation) + discovered a 3rd: a document's own name in a query can drown out retrieval entirely | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| 🔄 Day 22 | LangChain Basics | LCEL Chains · PromptTemplate · Memory | In progress | Coming |
| ⏳ Day 23 | AI Agents | Function Calling · ReAct Loop · Tool Use | — | Coming |
| ⏳ Day 24 | **PROJECT: RAG Chatbot** | ChromaDB · Gradio Chat · HF Spaces | — | Coming |

---

### ⏳ Phase 4: Deploy & Ship

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ⏳ Day 25 | FastAPI | REST API · Pydantic · Swagger UI | — | Coming |
| ⏳ Day 26 | Streamlit / Gradio UI | Demo GIF · Chat Interface · Polish | — | Coming |
| ⏳ Day 27 | Docker | Dockerfile · docker-compose | — | Coming |
| ⏳ Day 28 | Deploy to Render + HF Spaces | Live URL · Environment Vars · CI/CD | — | Coming |
| ⏳ Day 29 | GitHub Portfolio Cleanup | README · Badges · Pinned Repos | — | Coming |
| ⏳ Day 30 | Interview Prep | 30 Q&As · STAR Format · Reflection | — | Coming |

---

## 🚀 Live Projects (Built During Roadmap)

| Project | Stack | Live Demo | Status |
|---------|-------|-----------|--------|
| 🖼️ Image Classifier | PyTorch · ResNet · Gradio | [HuggingFace Spaces](https://huggingface.co/spaces/faisalimam19/plant-disease-classifier) | ✅ Deployed |
| 🤗 NLP Multi-Tool | BERT · HuggingFace · Streamlit | [nlp-multitool-app.streamlit.app](https://nlp-multitool-app.streamlit.app) | ✅ Deployed |
| 🤖 RAG Chatbot (Indian Law: BNS, Constitution, Evidence Act) | LangChain · ChromaDB · Hybrid Search · Gradio | Coming Day 24 | 🔄 Building |
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
| Vanishing Gradient | RNN gradient steps 1–10: 0.000000 vs steps 90–100: 0.002065 |
| Silent Bugs Found | BCELoss saturation + imbalanced dataset loader — both caught and fixed |

### Phase 2 — HuggingFace & Transformers

| Concept | What I Proved |
|---------|--------------|
| Attention from Scratch | Built Q/K/V attention in pure NumPy — visualized heatmap for 3-token and 6-token sequences |
| Positional Encoding | Proved every position gets a unique sinusoidal fingerprint — no two rows identical |
| Sentiment Bias | Neutral sentence ("okay, nothing special") → NEGATIVE 0.983 — exposed training data bias |
| NER Label Gap | Model detected PER/ORG/LOC — missed DATE class (not in CoNLL-03 label space) |
| Summarization | 116 words → 36 words (69% compression) with BART — identified first-paragraph bias |
| QA — Unanswerable | SQuAD2 model returned empty string + 0.0000 confidence when answer not in context |
| Zero-Shot Classification | One MNLI model classified text into topic/urgency/department with no task-specific training |
| BPE vs WordPiece | BERT (30k vocab) vs GPT2 (50k vocab) — different split points on identical input |
| Silent Truncation | 670 tokens truncated to 512 — 23.6% of data lost silently |
| Edge Cases | Emojis → [UNK] · Hindi → character explosion (6 words = 17 tokens) · Numbers → no numeric understanding |
| Fine-tuning BERT | **F1: 0.921** on IMDB · 20k train · 3 epochs · lr=2e-5 · T4 GPU · [Model live on HuggingFace Hub](https://huggingface.co/faisalimam19/bert-imdb-sentiment) |
| BERT Failure Mode | Sarcasm: "truly masterful... put me to sleep" → POSITIVE 0.976 — BERT reads words, not intent |
| ROUGE-2 Paradox | Partial summary (0.381) beat good summary (0.351) — exact copy scores 1.000 |
| Semantic Search | Built retrieval in 8 lines — vocabulary gap: "AI systems using real documents" → RAG scored only 0.365 |
| LoRA Efficiency | GPT-2 fine-tuned with 0.65% parameters (811k/125M) — 3.1MB adapter vs 475MB full model = **99.3% storage saving** |

### Phase 3 — LLMs & RAG

| Concept | What I Proved |
|---------|--------------|
| Temperature | 0.0 deterministic · 0.7 balanced · 1.5 unpredictable — temperature is a randomness dial, not a quality dial |
| JSON Mode | Structured sentiment + topics + summary extracted from raw text — parseable Python dict, no training needed |
| API Memory | Model has zero memory between calls — all context must be passed explicitly in every request |
| Zero-Shot vs Few-Shot | Zero-shot returned a paragraph; few-shot returned exactly one word — format enforcement is everything |
| Chain-of-Thought | CoT traced $9.00 answer step-by-step — debugging trail when answer is wrong; direct answer gives nothing |
| ReAct Pattern | Agent completed Thought→Action→Observe loop — calculated 3,686,400 docs/day across 4 iterations |
| Agent Failure Mode | Model called two Actions before first Observation — broke the loop; course-corrected on next turn |
| Prompt Injection | V1 system prompt leaked all instructions + disabled constraints · V2 hardened prompt held on all 3 attack patterns |
| Vector Search vs Keyword | "food and cooking" query: keyword search ranked unrelated ML sentences above the correct answer (0 word overlap for all 3); semantic search ranked the correct answer 1st at 0.410 |
| Cosine Similarity Geometry | Negative similarity confirmed (-0.044) between semantically opposite sentences — proved direction, not just distance, encodes meaning |
| Real-World RAG on Indian Law | Built full pipeline on Bharatiya Nyaya Sanhita (BNS) 2023, 237 pages, 77,343 words — extracted, chunked, embedded, retrieved, and grounded with page-level citations |
| Hallucination vs Grounding | Same question asked with/without RAG: without RAG, LLM falsely claimed BNS "isn't in effect yet" and cited the wrong (IPC) section; with RAG, model correctly refused rather than repeat the false claim |
| Chunking Bug Found & Fixed | Fixed-size 500-word chunks truncated Section 103's punishment clause mid-sentence; structure-aware chunking (split on the law's own 356 section boundaries, matching ~358 real BNS sections) fixed it completely |
| Hidden Document Contamination | Found TWO separate front-matter documents (table of contents + a BNS↔IPC cross-reference table) silently polluting retrieval — fixed by correctly locating the Act's true starting boundary |
| Hybrid Search (BM25 + RRF) | Combined keyword + semantic rankings via Reciprocal Rank Fusion — correctly surfaced Section 103 (murder) alongside legally-related Sections 109 and 55 |
| Query Formulation Bug | Discovered a document's own name inside a query ("...of the Bharatiya Nyaya Sanhita?") can outrank the actual answer in both BM25 and semantic search — confirmed by removing the phrase and watching retrieval correct itself |

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
[![HuggingFace](https://img.shields.io/badge/HuggingFace-faisalimam19-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/faisalimam19)
[![GitHub](https://img.shields.io/badge/GitHub-faisalimam1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/faisalimam1)

---

*Updated daily — every result in this README was actually measured, not estimated.*

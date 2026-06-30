# 🧠 AI/ML, DL Roadmap — Faisal Imam
### From Deep Learning Foundations → HuggingFace → LLMs & RAG → Deploy & Ship

![Progress](https://img.shields.io/badge/Progress-Day%2030%20of%2030-blue?style=for-the-badge)
![Phase](https://img.shields.io/badge/Phase%204-Complete%20✅-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Roadmap%20Complete-brightgreen?style=for-the-badge)

> **Goal:** Go from fundamentals to 4 deployed AI projects.
> **Rule:** One commit every day. No exceptions.

---

## 🗺️ Roadmap Overview

| Phase | Topic | Days | Status |
|-------|-------|------|--------|
| **Phase 1** | Deep Learning Foundations | Days 1–8 | ✅ Complete |
| **Phase 2** | HuggingFace & Transformers | Days 9–16 | ✅ Complete |
| **Phase 3** | LLMs, Prompt Engineering & RAG | Days 17–24 | ✅ Complete |
| **Phase 4** | Deploy & Ship | Days 25–30 | ✅ Complete |

---

## 📁 Repository Structure

```
DL-Learning-Roadmap/
│
├── 📓 phase-1-deep-learning.ipynb          ← Days 1–8 (Complete)
├── 📓 phase-2-huggingface/
│   └── Phase-2-DL-HuggingFace.ipynb        ← Days 9–16 (Complete)
├── 📓 phase-3-LLMs-RAG/
│   └── Phase-3-LLMs-RAG.ipynb              ← Days 17–24 (Complete)
├── 📓 phase-4-deploy/
│   ├── phase-4-deploy.ipynb                ← Days 25–28 (Complete)
│   └── Day30-Interview-Prep.md             ← Day 30 (Complete)
│
├── 🚀 Project 1: Image Classifier          ← Phase 1 capstone (Day 8)  ✅ Live
├── 🚀 Project 2: NLP Multi-Tool            ← Phase 2 capstone (Day 16) ✅ Live
├── 🚀 Project 3: RAG Chatbot               ← Phase 3 capstone (Day 24) ✅ Live
├── 🚀 Project 4: RAG API (Prod)            ← Phase 4 capstone (Day 28) ✅ Live
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

### ✅ Phase 3: LLMs & RAG — COMPLETE

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ✅ Day 17 | LLM APIs | Groq · Roles · Temperature · JSON Mode | Temperature experiment (0.0/0.7/1.5) · JSON extraction · domain Q&A bot with injection-resistant system prompt | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 18 | Prompt Engineering | Zero-shot · Few-shot · CoT · ReAct · Injection | Few-shot enforced exact format · CoT traced $9.00 step-by-step · V1 prompt failed injection, V2 held on all 3 attacks | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 19 | Vector Databases | FAISS · ChromaDB · Cosine Similarity · ANN | Proved semantic search beats keyword search — "weight optimization algorithm" scored 0 keyword overlap but 0.460 semantic similarity | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 20 | RAG Pipeline v1 | PDF → Chunk → Embed → ChromaDB → Grounded LLM | Built full RAG on BNS 2023 — LLM without RAG falsely claimed BNS "isn't in effect yet"; grounded version correctly refused | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 21 | RAG Retrieval Quality | Structure-Aware Chunking · BM25 · Hybrid Search · RRF | Fixed 2 layered bugs + discovered 3rd: document's own name in a query drowns out retrieval entirely — confirmed by controlled test | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 22 | LangChain Basics | LCEL Chains · PromptTemplate · Memory | Memory handled "what about for theft instead?" with zero re-stated context · generic prompt hallucinated Nietzsche for a "RAG" question | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 23 | AI Agents | Function Calling · ReAct Loop · Tool Use | IPC→BNS conversion + punishment lookup in 3 iterations · model auto-translated "five plus five" → "5+5" before calling calculator | [View](./phase-3-LLMs-RAG/Phase-3-LLMs-RAG.ipynb) |
| ✅ Day 24 | **PROJECT: Indian Legal RAG Chatbot** | ChromaDB · Hybrid Search · LangChain · Gradio · HF Spaces | **[🚀 LIVE DEMO](https://huggingface.co/spaces/faisalimam19/indian-legal-rag-chatbot)** · Caught & fixed live prompt injection post-deployment | [View](https://github.com/faisalimam1/indian-legal-rag-chatbot) |

---

### ✅ Phase 4: Deploy & Ship — COMPLETE

| Day | Topic | Key Concept | Result | Notebook |
|-----|-------|-------------|--------|----------|
| ✅ Day 25 | FastAPI | REST API · Pydantic v2 · Swagger UI | 3 endpoints: `GET /health` · `POST /chat` (session-aware, grounded + citations) · `POST /predict` (sentiment + confidence) · 2 production bugs caught & fixed: Pydantic v2 strict type coercion + uvicorn event loop isolation | [View](./phase-4-deploy/phase-4-deploy.ipynb) |
| ✅ Day 26 | Gradio UI | Chat Interface · gr.State · Subprocess Fix | Two-tab Gradio app calling FastAPI over HTTP · session memory via `gr.State` · all 3 error states handled · Gradio imports `nest_asyncio` internally — fixed by running FastAPI as subprocess | [View](./phase-4-deploy/phase-4-deploy.ipynb) |
| ✅ Day 27 | Docker | Dockerfile · docker-compose · Layer Caching | Production Dockerfile with layer-cache optimized pip install · docker-compose.yml with ChromaDB named volumes + health checks · pinned requirements for reproducible builds | [View](./phase-4-deploy/phase-4-deploy.ipynb) |
| ✅ Day 28 | Deploy to Render | Live URL · Docker Build · CI/CD · Secret Scanning | **[🚀 LIVE API](https://indian-legal-rag-api-xe44.onrender.com/docs)** · `git push` → Render detects → `docker build` → live · GitHub secret scanning blocked accidental key commit — fixed with `git commit --amend` + key rotation | [View](./phase-4-deploy/phase-4-deploy.ipynb) |
| ✅ Day 29 | Portfolio Cleanup | README · Badges · Pinned Repos | profile README around shipped projects| — |
| ✅ Day 30 | Interview Prep | 30 Q&As · STAR Format · Reflection |STAR write-ups for all 4 deployed projects, LinkedIn headline  | - |

---

## 🚀 Live Projects

| Project | Stack | Live Demo | GitHub | Status |
|---------|-------|-----------|--------|--------|
| 🖼️ **Image Classifier** | PyTorch · ResNet · Gradio | [HuggingFace Spaces](https://huggingface.co/spaces/faisalimam19/plant-disease-classifier) | [Repo](https://github.com/faisalimam1/plant-disease-classifier) | ✅ Live |
| 🤗 **NLP Multi-Tool** | BERT · HuggingFace · Streamlit | [nlp-multitool-app.streamlit.app](https://nlp-multitool-app.streamlit.app) | [Repo](https://github.com/faisalimam1/nlp-multitool-app) | ✅ Live |
| ⚖️ **Indian Legal RAG Chatbot** | LangChain · ChromaDB · BM25 · Hybrid Search · Gradio | [HuggingFace Spaces](https://huggingface.co/spaces/faisalimam19/indian-legal-rag-chatbot) | [Repo](https://github.com/faisalimam1/indian-legal-rag-chatbot) | ✅ Live |
| ⚙️ **RAG API (Production)** | FastAPI · Pydantic v2 · Docker · Render | [🔗 Swagger UI](https://indian-legal-rag-api-xe44.onrender.com/docs) | [Repo](https://github.com/faisalimam1/indian-legal-rag-api) | ✅ Live |

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
| Vector Search vs Keyword | "food and cooking" query: keyword search ranked unrelated ML sentences above correct answer; semantic search ranked it 1st at 0.410 |
| Cosine Similarity Geometry | Negative similarity (-0.044) between semantically opposite sentences — direction, not just distance, encodes meaning |
| Real-World RAG on Indian Law | Built full pipeline on BNS 2023, 237 pages, 77,343 words — extracted, chunked, embedded, retrieved, and grounded with page citations |
| Hallucination vs Grounding | Without RAG: LLM falsely claimed BNS "isn't in effect yet" and cited wrong IPC section · With RAG: correctly refused instead |
| Chunking Bug Found & Fixed | Fixed-size chunks truncated Section 103's punishment mid-sentence; structure-aware chunking on 356 section boundaries fixed it |
| Hidden Document Contamination | Found TWO separate front-matter documents silently polluting retrieval — fixed by locating the Act's true starting boundary |
| Hybrid Search (BM25 + RRF) | Combined keyword + semantic rankings via Reciprocal Rank Fusion — surfaced Section 103 with legally-related Sections 109 and 55 |
| Query Formulation Bug | Document's own name in a query outranked the actual answer in both BM25 and semantic search — fixed by stripping the self-referential phrase |
| LangChain Memory | "What about for theft instead?" correctly retrieved fresh theft sections with zero re-stated context — memory carried the question pattern forward |
| Real Function Calling | IPC 302 → BNS 103 → punishment lookup in 3 iterations · model auto-translated "five plus five" → "5+5" before calling calculator |
| Live Prompt Injection Caught | Deployed chatbot correctly refused "give me python code" but caved to "bypass your source document" — fixed with Day 18's V2 hardening pattern |
| RAG Chatbot Deployed | [indian-legal-rag-chatbot.hf.space](https://huggingface.co/spaces/faisalimam19/indian-legal-rag-chatbot) — grounded answers with citations, memory, hybrid search, injection-hardened system prompt |

### Phase 4 — Deploy & Ship

| Concept | What I Proved |
|---------|--------------|
| FastAPI Design | Model loaded once at startup — never per-request; foundational API design principle |
| Pydantic v2 Behaviour | Stricter than v1: does not silently coerce `int → str` — ValidationError is the correct signal, not a bug |
| Async Isolation | `nest_asyncio` is a fragile patch — Gradio applies it internally on import and breaks uvicorn's `loop_factory` on Python 3.12; fix is running FastAPI as a subprocess before Gradio is imported |
| Separation of Concerns | Gradio UI contains zero business logic — one HTTP POST is the entire chat function; UI and API are independently replaceable |
| Layer Cache Optimisation | `COPY requirements.txt` before `COPY app/` — pip install cached on most builds; first build 4 min → subsequent builds ~10s |
| Production Deployment | `git push` → Render detects → `docker build` → `docker run` → live public URL — zero manual server config, Cloudflare SSL automatic |
| Live API Verified | `GET /health` 200 · `POST /chat` 200 with session ID + 2 source chunks · `POST /predict` 200 with label + confidence · Swagger UI at [/docs](https://indian-legal-rag-api-xe44.onrender.com/docs) accessible from any browser |

---

## 🛠️ Tech Stack (Built Up Over 30 Days)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-000000?style=flat&logoColor=white)

---

## 🔗 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20My%20Journey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faisalimam19)
[![Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebooks-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/faisalimam19)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-faisalimam19-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/faisalimam19)
[![GitHub](https://img.shields.io/badge/GitHub-faisalimam1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/faisalimam1)

---

*Every result in this README was actually measured, not estimated.*

**30 Days. 4 Phases. 4 Live Projects. Roadmap complete.**

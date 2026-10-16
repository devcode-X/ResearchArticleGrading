# 📄 RAG-Powered Research Paper Evaluator — Automated Conference Paper Grading

> **Finalist, KDSH 2025 Hackathon** · Built a multi-agent RAG pipeline that auto-evaluates academic research papers for conference publishability using the Pathway streaming framework and LLMs.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![Pathway](https://img.shields.io/badge/Pathway-Streaming-FF6B35?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Pipeline-6B46C1?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-Powered-412991?style=flat-square)

---

## 🎯 What It Does

Manual peer review of research papers is slow, expensive, and inconsistent. **RAG 101** automates the conference paper evaluation pipeline — ingesting PDFs in real-time, running multi-dimensional quality assessments via an LLM + RAG system, and producing structured publishability scores.

Built end-to-end at **KDSH 2025** (IIT Kharagpur's Data Science Hackathon) — reached the **semifinals**.

---

## ✨ Features

- **📥 Streaming Ingestion** — real-time paper ingestion via Pathway's document processing pipeline
- **🔍 RAG-Based Evaluation** — retrieves relevant domain context to benchmark paper quality against existing literature
- **📊 Multi-Dimensional Scoring** — evaluates novelty, methodology rigor, clarity, and impact
- **🤖 LLM Judge** — uses language models to generate structured review commentary
- **⚡ Automated Publishability Decision** — accept / reject / revise with justification

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Streaming Framework | Pathway |
| RAG Pipeline | LangChain / Custom |
| LLM Backend | OpenAI GPT / Gemini |
| Embeddings | Sentence Transformers |
| Language | Python 3.10+ |

---

## 🚀 Quick Start

```bash
git clone https://github.com/devcode-X/ResearchArticleGrading
cd ResearchArticleGrading
pip install -r requirements.txt

# Set your API key
export OPENAI_API_KEY=your_key_here

# Run the evaluation pipeline
python main.py --paper path/to/paper.pdf
```

---

## 📁 Structure

```
ResearchArticleGrading/
├── pipeline/          # Pathway streaming ingestion
├── rag/               # RAG retrieval & context building
├── evaluation/        # LLM grading logic
├── data/              # Sample papers & ground truth
└── main.py
```

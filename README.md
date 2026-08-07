# Enhanced HuggingFace NLP/LLM Course Notebooks

A personal, deeply-annotated version of the [HuggingFace LLM Course](https://huggingface.co/learn/llm-course/), built while learning the course from scratch over ~2 months (no prior NLP/LLM background, coming from a PyTorch/Computer Vision foundation).

## Why this exists

HuggingFace's official course notebooks (available on GitHub) contain **code only** — no explanations. Their detailed explanations live separately in the web documentation, which **cannot be downloaded or run alongside the code**.

This repo merges both into single, self-contained notebooks:
- ✅ Full course code, chapter by chapter
- ✅ Detailed notes and explanations written in plain, beginner-friendly language, directly alongside the code
- ✅ Fixes for outdated/broken code caused by library version changes (e.g. `transformers` v5 removing several `pipeline()` task names)
- ✅ Fixes for dead dataset URLs used in the original course
- ✅ Windows-specific fixes (the official course assumes Linux/Colab — commands like `wget`, `gzip`, `unzip` don't work natively on Windows)
- ✅ Extra clarifying examples and analogies for concepts that are easy to misunderstand on a first pass (tokenization, embeddings, attention, chat templates, etc.)

## What's covered

Chapters 1–7 and Chapter 11 of the HuggingFace LLM Course in full depth, including:
- Transformer architecture fundamentals
- Tokenizers (training, BPE/WordPiece/Unigram concepts)
- The `transformers` and `datasets` libraries
- Fine-tuning with `Trainer` and raw PyTorch training loops
- Token classification, masked language modeling, causal LM training from scratch
- Semantic search with FAISS
- Chat templates, Supervised Fine-Tuning (SFT), and LoRA

**Chapter 9 (Building and sharing demos / Gradio)** and **Chapter 10 (Curate high-quality datasets / Argilla)** are covered at a conceptual/overview level only (notes included, hands-on setup skipped) — both are UI/third-party tool chapters with minimal transferable ML concepts.

**Chapters intentionally skipped in full:**
- **Chapter 8 (How to ask for help)** — debugging/forum-etiquette guide, not core ML content
- **Chapter 12 (Build Reasoning Models / GRPO)** — advanced RL-research-level content, outside the scope of applied AI/ML Engineer work

## Who this is for

Anyone going through the official HuggingFace course who wants:
- Explanations alongside the code, not spread across a separate webpage
- Fixes for common errors caused by library updates
- A beginner-friendly second voice explaining *why*, not just *what*

## How to use

Each notebook corresponds to a chapter/section of the course. Open in Jupyter, VS Code, or Google Colab and follow along. Notebooks are meant to be read top to bottom like a study guide, not just executed.

## Related
Also check out my annotated Vector Database & ChromaDB notes:  
👉 [Annotated-VectorDB-ChromaDB-Course](https://github.com/rehan-ml/Annotated-VectorDB-ChromaDB-Course)

## Credit

All original course content, structure, and exercises belong to [HuggingFace](https://huggingface.co/learn/llm-course/) and its authors. This repository is an educational derivative — annotated, corrected, and expanded for personal learning purposes, shared publicly in case it helps others.

## License

MIT License — see [LICENSE](LICENSE) file. Free to use, modify, and share.

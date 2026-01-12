# Rahul Jangra

Applied Machine Learning Engineer focused on **LLM training dynamics, evaluation, and inference efficiency**.

I work on the parts of ML systems that usually break first:  
training stability, memory bottlenecks, retrieval failures, and evaluation blind spots.

---

## What I Actually Work On

**Large Language Models**
- Instruction tuning (SFT, DPO) and failure analysis
- Attention behavior, KV caching, and long-context issues
- Dataset quality, collapse modes, and reward hacking

**ML Systems & Performance**
- PyTorch internals (autograd, checkpointing, mixed precision)
- Distributed training (DDP, FSDP, memory tradeoffs)
- Inference optimization (vLLM-style serving, quantization, latency vs throughput)

**Evaluation (Underrated, Critical)**
- Task-specific evaluation harnesses
- Regression detection across model versions
- Retrieval quality diagnostics for RAG systems

---

## Selected Work

### Instruction Tuning & Model Behavior Analysis
- Analyzed instruction collapse during fine-tuning on noisy datasets
- Compared SFT vs DPO using task-specific win-rate metrics
- Identified normalization and RoPE scaling effects on training stability

### Retrieval-Augmented Generation (RAG)
- Designed retrieval pipelines with hybrid search (dense + sparse)
- Evaluated hallucination sources caused by embedding drift and chunking
- Built retrieval-quality metrics beyond end-task accuracy

### Training & Inference Optimization
- Reduced GPU memory usage using gradient checkpointing and mixed precision
- Benchmarked inference latency improvements via KV cache reuse and quantization
- Investigated tradeoffs between throughput, batch size, and response time

---

## Technical Stack (Weighted)

**Core**
- Python, PyTorch (deep internals focus)

**LLMs**
- Transformers, attention variants, KV caching
- SFT, DPO, reward modeling concepts

**Systems**
- Distributed training (DDP, FSDP)
- Mixed precision, memory optimization

**Inference**
- Quantization (INT8 / GPTQ-style)
- Serving and performance tuning

**Evaluation**
- Custom metrics, regression testing
- Dataset and retrieval diagnostics

---

## Philosophy

Most ML failures are not caused by models being too small.  
They come from **poor evaluation, unstable training, and unexamined assumptions**.

I care about:
- Why something fails
- How to detect it early
- How to fix it without scaling blindly

---

## Notes

- Repositories here are **focused experiments**, not tutorials
- Each project prioritizes *analysis, metrics, and failure cases*
- I value depth over breadth and signal over noise

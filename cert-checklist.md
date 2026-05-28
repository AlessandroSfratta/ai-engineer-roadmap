# AI ENGINEERING SKILLS CHECKLIST — CERT

> **Fonte:** [gratitudedriven.com](https://gratitudedriven.com) — AI Engineering Skills Checklist
>
> Ogni voce è mappata a uno Step della roadmap (`road-map-completa.md`).
> Quando lo Step viene completato, l'agente AI contrassegna le voci corrispondenti con `[x]`.

## 🤖 ISTRUZIONI PER L'AGENTE AI

> Quando completi uno Step della roadmap:
> 1. Apri questo file e trova tutte le voci che riportano lo Step appena completato
> 2. Cambia `[ ]` in `[x]` per ogni voce coperta dallo Step
> 3. Aggiungi una breve nota di cosa l'utente ha imparato (es. _"Completato: sai usare pytest, fixtures, coverage"_)
> 4. Nella roadmap, contrassegna il badge `🟨 CERT` dello step con `✅`

---

## CERT-SWE — Software Engineering (Technical Foundation)

- [x] **Python programming** — Sintassi, funzioni, I/O, eccezioni, moduli, OOP, typing — _Step 2, 3_ — ✅ _Corso Master "Programmazione con Python" completato_
- [x] **Understanding of numerical precision formats** — float16, float32, bfloat16 e impatto su ML/inference — _Step 1_
- [x] **Linux & command-line tools** — Navigazione filesystem, scripting bash, ssh, pipe, redirect — _Step 1_
- [x] **Git and version control** — Branch, commit, merge, README, git flow basics — _Step 1_
- [x] **Data structures and algorithms fundamentals** — Complessità Big-O, liste, dizionari, set, code, stack, alberi — _Step 2_ — ✅ _Studiati fondamenti e complessità per ML engineer_
- [ ] **Testing** — pytest, fixtures, mocking, coverage, CI/CD pipeline — _Step 4_
- [ ] **API design and integration** — REST design, endpoint contracts, versioning, input validation — _Step 9_
- [ ] **System architecture concepts** — Microservices vs monolith, API gateway patterns, scalabilità — _Step 9_
- [ ] **Basic understanding of Docker and containers** — Dockerfile, multi-stage builds, compose, networking — _Step 10_
- [ ] **Cloud platforms** — GCP/AWS/Azure basics, compute instances, storage, managed services — _Step 10_
- [ ] **Monitoring and logging** — Structured logs, metriche, alerting, Prometheus/Grafana basics — _Step 10_
- [ ] **Basic statistics and probability** — Distribuzioni (normale, binomiale, Poisson), Bayes, test di ipotesi, p-value — _Step 6_
- [ ] **Basic linear algebra** — Vettori, matrici, operazioni, eigenvalues, SVD (fondamentali per embeddings/transformers) — _Step 6_
- [ ] **Basic calculus** — Derivate, gradiente, chain rule (fondamentali per backpropagation) — _Step 6_

---

## CERT-ML — ML Basics

- [ ] **Understanding of supervised/unsupervised learning** — Classificazione, regressione, clustering, dimensionality reduction — _Step 6_
- [ ] **Model evaluation metrics** — Accuracy, precision, recall, F1, AUC-ROC, confusion matrix — _Step 6_
- [ ] **Training/validation/test splits** — Strategie di split, stratificazione, data leakage prevention — _Step 6_
- [ ] **Common algorithms at a high level** — Decision trees, random forest, SVM, k-means, PCA — _Step 7_
- [ ] **Overfitting and underfitting** — Bias-variance tradeoff, regularizzazione, early stopping, cross-validation — _Step 7_

---

## CERT-DS — Dataset Engineering

- [ ] **Data acquisition strategies** — Web scraping, API, synthetic data generation, data sourcing — _Step 7.5_
- [ ] **Data quality assessment** — Completezza, consistenza, accuratezza, freshness, data profiling — _Step 7.5_
- [ ] **Data processing** — Cleaning, normalization, deduplication, outlier handling, pipeline ETL — _Step 7.5_
- [ ] **Annotation guidelines creation** — Inter-annotator agreement, Label Studio, quality control — _Step 7.5_
- [ ] **Data augmentation and synthesis** — NLP augmentation, paraphrasing, backtranslation, data mixing — _Step 7.5_

---

## CERT-FM — Foundation Models & Model Selection

- [ ] **Strong deep learning knowledge** — Reti neurali, backpropagation, loss functions, ottimizzatori — _Step 15_
- [ ] **Transformer architecture** — Encoder/decoder, layer normalization, feed-forward, positional encoding — _Step 15_
- [ ] **Attention mechanism** — Self-attention, multi-head attention, KV cache, flash attention — _Step 15_
- [ ] **Tokenization** — BPE, SentencePiece, tiktoken, context window, token budget — _Step 15_
- [ ] **Model scaling laws** — Chinchilla, compute-optimal training, emergent abilities — _Step 15_
- [ ] **Post-training techniques: SFT, RLHF, DPO** — Supervised fine-tuning, reward models, preference optimization, ORPO — _Step 15_
- [ ] **Tradeoffs: cost vs performance vs licensing** — $/1M tokens, latency, throughput, terms of use — _Step 15_
- [ ] **Open-weight vs open-source vs API models** — Llama, Mistral, GPT, Claude, licensing implications — _Step 15_
- [ ] **Tooling for model benchmarking** — lm-evaluation-harness, HELM, custom evals, leaderboards — _Step 15_

---

## CERT-FT — Fine-tuning

- [ ] **Parameter-efficient fine-tuning (PEFT)** — Perché e quando usarlo, confronto con full fine-tuning — _Step 15.5_
- [ ] **LoRA and similar approaches** — QLoRA, AdaLoRA, Adapters, rank selection, target modules — _Step 15.5_
- [ ] **Model distillation** — Knowledge transfer, teacher-student, output matching — _Step 15.5_
- [ ] **Model merging** — SLERP, TIES, DARE, mergekit, use cases — _Step 15.5_
- [ ] **Multi-task fine-tuning** — Instruction tuning, task vectors, mixture training — _Step 15.5_

---

## CERT-EVAL — Evaluation and Testing

- [ ] **Evaluation metrics** — Perplexity, BLEU, ROUGE, semantic similarity, functional correctness — _Step 19_
- [ ] **Model evaluation pipelines** — Automated eval, regression testing, benchmark suites — _Step 22_
- [ ] **Using AI judges and human evals** — LLM-as-judge, RLHF data collection, inter-rater reliability — _Step 22_
- [ ] **Measuring hallucinations, toxicity, bias** — TruthfulQA, ToxiGen, bias benchmarks, red teaming — _Step 22_

---

## CERT-PE — Prompt Engineering

- [ ] **Structuring effective prompts** — System/user/assistant roles, formatting, constraints, output structure — _Step 17_
- [ ] **In-context learning techniques** — Zero-shot, few-shot, chain-of-thought, tree-of-thought — _Step 17_
- [ ] **Defensive prompt engineering** — Prompt injection detection, jailbreak prevention, input sanitization — _Step 17_
- [ ] **Prompt experimentation and tracking** — Versioning, A/B testing, promptfoo, langfuse — _Step 17_

---

## CERT-RAG — Retrieval-Augmented Generation

- [ ] **Embedding techniques** — Dense embeddings, sentence transformers, embedding models selection — _Step 19_
- [ ] **Term-based vs embedding-based retrieval** — BM25 vs dense vectors, hybrid search, reciprocal rank fusion — _Step 19_
- [ ] **Vector database implementation** — Pinecone, ChromaDB, indexing, metadata filtering, namespaces — _Step 20_
- [ ] **Document chunking strategies** — Fixed size, semantic, recursive, parent-child, overlap — _Step 20_
- [ ] **Retrieval optimization techniques** — Reranking, query expansion, HyDE, Cohere rerank — _Step 20_

---

## CERT-AGT — Agent Systems

- [ ] **Tool integration** — Function calling, tool schemas, error handling, fallbacks — _Step 21_
- [ ] **Planning techniques** — ReAct, Chain-of-Thought, Tree-of-Thought, Plan-and-Solve — _Step 21_
- [ ] **Memory systems implementation** — Conversation memory, entity memory, summary memory — _Step 21_
- [ ] **Agent security and safety guardrails** — Tool restrictions, output validation, scope limiting — _Step 21_
- [ ] **Agent evaluation methodologies** — Task success rate, tool call accuracy, multi-step benchmarks — _Step 21_

---

## CERT-INF — Inference Optimization

- [ ] **Understanding compute vs memory-bound inference** — Bottleneck analysis, roofline model, arithmetic intensity — _Step 22_
- [ ] **Latency metrics: TTFT, TPOT** — Time to First Token, Time Per Output Token, P50/P99 — _Step 22_
- [ ] **Model compression: quantization, pruning, distillation** — GPTQ, AWQ, GGUF, structured pruning — _Step 22_
- [ ] **Batch vs online inference strategies** — Throughput vs latency tradeoffs, queueing, SLAs — _Step 22_
- [ ] **Hardware (GPU, TPU, memory specs)** — A100, H100, VRAM planning, TPU v4/v5 — _Step 22_
- [ ] **Batching techniques** — Continuous batching, dynamic batching, padding strategies — _Step 22_
- [ ] **Parallel inference strategies** — Tensor parallelism, pipeline parallelism, data parallelism — _Step 22_
- [ ] **Caching implementations** — KV cache, prefix caching, semantic caching — _Step 22_

---

## CERT-APP — Application Architecture

- [ ] **Context construction patterns** — Dynamic context assembly, prompt templating, retrieval integration — _Step 20_
- [ ] **Input/output guardrails** — Content filtering, format validation, toxicity detection — _Step 22_
- [ ] **Model routing and gateways** — Load balancing, fallbacks, model selection logic — _Step 22_
- [ ] **Caching architectures** — Semantic caching, prompt caching, response deduplication — _Step 22_
- [ ] **Orchestration patterns** — Async processing, queue-based architectures, event-driven — _Step 22_

---

## CERT-SEC — Security, Privacy & Ethics

- [ ] **PII detection and redaction** — Regex patterns, NER-based detection, presidio, anonymization — _Step 14_
- [ ] **Prompt injection detection/mitigation** — Input sanitization, canary tokens, classifier-based detection — _Step 17_
- [ ] **Adversarial input handling** — Jailbreak detection, content moderation, red teaming — _Step 22_
- [ ] **Secure sandboxing** — Code execution safety, tool call restrictions, container isolation — _Step 22_
- [ ] **Model privacy risks** — Memorization attacks, data leakage, training data extraction — _Step 22_
- [ ] **Legal compliance (GDPR, copyright)** — Data retention, right to erasure, AI Act (EU), copyright implications — _Step 22_
- [ ] **AI Ethics considerations** — Fairness, transparency, accountability, bias mitigation — _Step 22_

---

## CERT-FB — User Feedback Integration

- [ ] **Feedback system design** — Thumbs up/down, ratings, free text, structured feedback forms — _Step 22_
- [ ] **Explicit vs implicit feedback collection** — Direct user signals vs behavioral signals (clicks, dwell time) — _Step 22_
- [ ] **Data flywheels** — Using feedback to improve models, continuous data collection, self-improving systems — _Step 22_
- [ ] **Human-in-the-loop approaches** — HITL for edge cases, active learning, escalation policies — _Step 22_
- [ ] **Continuous improvement cycles** — Monitoring → feedback → retrain loop, A/B testing, canary deployments — _Step 22_

---

## 📊 Riepilogo Copertura per Step

| Step | CERT coperti |
|------|-------------|
| 1 ✅ | CERT-SWE (numerical precision, Linux, Git) |
| 2 ✅ | CERT-SWE (Python, DSA) |
| 3 ✅ | CERT-SWE (Python avanzato) |
| 4 | CERT-SWE (Testing) |
| 5 | _(nessun CERT diretto — consolida SWE)_ |
| 6 | CERT-SWE (stats, linalg, calculus) + CERT-ML (supervised, metrics, splits) |
| 7 | CERT-ML (algorithms, overfitting) |
| 7.5 | CERT-DS (tutti) |
| 8 | _(progetto — consolida CERT-ML)_ |
| 9 | CERT-SWE (API design, system architecture) |
| 10 | CERT-SWE (Docker, Cloud, Monitoring) |
| 11 | _(nessun CERT diretto — pratica SQL)_ |
| 12 | _(progetto — pratica SQL)_ |
| 13 | _(nessun CERT diretto — pratica NoSQL)_ |
| 14 | CERT-SEC (PII detection) |
| 15 | CERT-FM (tutti) |
| 15.5 | CERT-FT (tutti) |
| 16 | _(hands-on — consolida CERT-FM)_ |
| 17 | CERT-PE (tutti) + CERT-SEC (prompt injection) |
| 18 | _(progetto — consolida CERT-PE)_ |
| 19 | CERT-RAG (embedding, retrieval) + CERT-EVAL (metrics) |
| 20 | CERT-RAG (vector DB, chunking, optimization) + CERT-APP (context patterns) |
| 21 | CERT-AGT (tutti) |
| 22 | CERT-INF + CERT-APP + CERT-EVAL + CERT-SEC + CERT-FB (tutti) |

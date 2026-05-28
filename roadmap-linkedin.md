# AI Engineer Roadmap - Public Edition

> Roadmap personale per costruire competenze da AI Engineer, con focus su software engineering, machine learning, LLM, RAG, agenti AI, LLMOps, sicurezza e preparazione ai colloqui tecnici.
>
> Questa versione è pensata per LinkedIn e portfolio: mostra direzione, metodo, competenze e deliverable senza includere note operative personali.

Ultimo aggiornamento: 28/05/2026

## Come leggere la roadmap

Legenda stato:

- ✅ **Completata**: step già studiato e validato con output pratico
- ⏳ **In corso**: step attivo
- 🕒 **Pianificata**: step da affrontare

Legenda badge:

- 🟦 **MASTER**: moduli o progetti del percorso formativo principale
- 🟩 **DATACAMP**: corsi o capitoli di supporto pratico
- 🟨 **CERT**: competenze mappate alla checklist AI Engineering
- 🔎 **RESEARCH**: studio autonomo da documentazione, paper, articoli o tutorial tecnici
- 🆕 **SKILLS**: competenze professionali aggiunte alla roadmap

## Obiettivo

L'obiettivo è trasformare lo studio in una sequenza di progetti verificabili: codice, notebook, API, report, demo, checklist di produzione e preparazione ai colloqui.

Il percorso non è solo teorico. Ogni fase deve produrre almeno uno tra:

- repository portfolio
- notebook riproducibile
- API o servizio deployabile
- report tecnico
- checklist di qualità, sicurezza o produzione
- mock interview o risposta tecnica strutturata

## Stato attuale

| Stato | Area | Step |
| ----- | ---- | ---- |
| ✅ | Software Engineering foundations | Step 1-3 |
| ⏳ | Testing e manutenibilità | Step 4 |
| 🕒 | Reliability, ML, LLM, RAG, Agentic AI, LLMOps | Step 5-23 |

---

## ✅ Step 1 - Setup + Workflow Pro

**Focus:** ambiente tecnico pronto per lavorare come AI engineer.

**Competenze**

- Setup Python, Colab e repository
- Git, branch, commit e README
- Linux, shell e scripting base
- Precisione numerica: float16, float32, bfloat16

**Badge**

- 🟦 MASTER: Google Colab e pensiero computazionale
- 🟩 DATACAMP: non applicabile
- 🟨 CERT: CERT-SWE - Git, Linux, numerical precision
- 🔎 RESEARCH: poetry/venv, pre-commit, git flow, bash scripting

**Output:** repository base con setup, README e workflow riproducibile.

---

## ✅ Step 2 - Python Core

**Focus:** scrivere Python in modo fluido e leggibile.

**Competenze**

- Funzioni, I/O, eccezioni e moduli
- Strutture dati fondamentali
- Complessità Big-O
- Primi pattern per codice manutenibile

**Badge**

- 🟦 MASTER: Programmazione con Python
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-SWE - Python programming, data structures, algorithms
- 🔎 RESEARCH: best practice di struttura progetto e DSA per ML engineer

**Output:** mini CLI tool con gestione input e logging base.

---

## ✅ Step 3 - OOP + Moduli + Typing

**Focus:** passare da script a package Python strutturati.

**Competenze**

- Classi, dataclass e typing
- Moduli installabili
- Docstring e interfacce chiare
- Primi standard di qualità del codice

**Badge**

- 🟦 MASTER: Programmazione con Python
- 🟩 DATACAMP: Software Engineering e scienza dei dati
- 🟨 CERT: CERT-SWE - OOP, typing, moduli
- 🔎 RESEARCH: mypy e typing quickstart

**Output:** package installabile con struttura pulita.

---

## ⏳ Step 4 - Testing + Manutenibilita

**Focus:** rendere il codice verificabile e sostenibile.

**Competenze**

- pytest
- fixture e casi limite
- logging
- refactor
- CI/CD iniziale

**Badge**

- 🟦 MASTER: Coding avanzato con Python
- 🟩 DATACAMP: Manutenibilita del codice
- 🟨 CERT: CERT-SWE - Testing, coverage, CI/CD
- 🔎 RESEARCH: GitHub Actions e cache pytest

**Output:** pipeline CI verde con coverage minimo e test riproducibili.

---

## 🕒 Step 5 - Reliability Engineering

**Focus:** costruire codice robusto, osservabile e prevedibile.

**Competenze**

- Error handling
- Retry e backoff
- Timeouts
- Logging strutturato
- Tassonomia degli errori

**Badge**

- 🟦 MASTER: Coding avanzato con Python
- 🟩 DATACAMP: manutenibilità, se utile
- 🟨 CERT: consolidamento software engineering
- 🔎 RESEARCH: timeouts, retries e fail-safe design

**Output:** libreria con logging strutturato e comportamento fail-safe.

---

## 🕒 Step 6 - ML Baseline + Math Foundations

**Focus:** costruire baseline ML solide e comprendere le basi matematiche essenziali.

**Competenze**

- Train/validation/test split
- Metriche di valutazione
- Data leakage
- Statistica e probabilità
- Algebra lineare
- Calcolo differenziale per gradienti e backpropagation

**Badge**

- 🟦 MASTER: AI applicata per sviluppatori
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-SWE math foundations + CERT-ML
- 🔎 RESEARCH: leakage examples, 3Blue1Brown, StatQuest

**Output:** notebook baseline con metriche, seed fisso e mini cheat sheet matematica.

---

## 🕒 Step 7 - ML Improvement + Evaluation

**Focus:** migliorare un modello con metodo, non per tentativi casuali.

**Competenze**

- Preprocessing
- Feature engineering
- Hyperparameter tuning
- Cross validation
- Error analysis
- Bias-variance tradeoff

**Badge**

- 🟦 MASTER: AI applicata per sviluppatori
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-ML - algorithms, overfitting, underfitting
- 🔎 RESEARCH: ablation study e cross validation

**Output:** primo progetto portfolio ML con confronto baseline -> modello migliorato.

---

## 🕒 Step 7.5 - Dataset Engineering

**Focus:** creare dataset di qualità per training, evaluation e fine-tuning.

**Competenze**

- Data acquisition
- Data quality assessment
- Cleaning e deduplicazione
- Annotation guidelines
- Data augmentation e synthetic data

**Badge**

- 🟦 MASTER: applicazione nei progetti
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-DS - acquisition, quality, processing, annotation, augmentation
- 🔎 RESEARCH: Snorkel, Label Studio, synthetic data generation

**Output:** pipeline dataset con quality report automatico.

---

## 🕒 Step 8 - Portfolio ML: Language Identification

**Focus:** completare un progetto ML end-to-end su classificazione testuale.

**Competenze**

- Text classification
- Language identification
- Metriche di classificazione
- Benchmarking
- README tecnico

**Badge**

- 🟦 MASTER: progetto identificazione lingua
- 🟩 DATACAMP: facoltativo
- 🟨 CERT: consolidamento CERT-ML
- 🔎 RESEARCH: fastText language identification

**Output:** progetto portfolio ML pulito, riproducibile e documentato.

---

## 🕒 Step 9 - REST API per ML

**Focus:** servire un modello ML tramite API.

**Competenze**

- FastAPI
- Contratti endpoint
- Input validation
- API versioning
- Health checks
- System architecture basics

**Badge**

- 🟦 MASTER: sviluppo REST API per Machine Learning
- 🟩 DATACAMP: preparing AI apps for production
- 🟨 CERT: CERT-SWE - API design e architecture concepts
- 🔎 RESEARCH: Pydantic validation e API versioning

**Output:** API `/predict` e `/health` con test di integrazione.

---

## 🕒 Step 10 - ML in Produzione

**Focus:** portare un modello da notebook a servizio deployabile.

**Competenze**

- Packaging
- Docker
- Cloud basics
- Logging e monitoring
- Healthcheck
- Metriche operative

**Badge**

- 🟦 MASTER: progetto messa in produzione
- 🟩 DATACAMP: production best practices
- 🟨 CERT: CERT-SWE - Docker, Cloud, Monitoring
- 🔎 RESEARCH: Docker FastAPI, Cloud Run, Prometheus/Grafana

**Output:** progetto portfolio dockerizzato con logging e metriche.

---

## 🕒 Step 11 - SQL Fundamentals

**Focus:** usare SQL in modo operativo per analisi e debugging dati.

**Competenze**

- Join
- Aggregazioni
- Query analysis
- KPI
- Ottimizzazione base

**Badge**

- 🟦 MASTER: database relazionali con SQL
- 🟩 DATACAMP: non specifico
- 🟨 CERT: pratica data engineering
- 🔎 RESEARCH: SQL optimization basics

**Output:** report SQL con query documentate e riproducibili.

---

## 🕒 Step 12 - Analytics Project: E-commerce Sales

**Focus:** trasformare dati grezzi in insight comunicabili.

**Competenze**

- Analisi vendite
- KPI
- Data storytelling
- Reportistica

**Badge**

- 🟦 MASTER: progetto analisi vendite e-commerce
- 🟩 DATACAMP: non specifico
- 🟨 CERT: progetto SQL
- 🔎 RESEARCH: data storytelling for analytics

**Output:** report finale con note su dataset e definizione KPI.

---

## 🕒 Step 13 - NoSQL + Data Processing

**Focus:** progettare pipeline dati su document store e dati semi-strutturati.

**Competenze**

- NoSQL mental model
- ETL
- Schema validation
- Data quality checks

**Badge**

- 🟦 MASTER: NoSQL per elaborazione dati
- 🟩 DATACAMP: non specifico
- 🟨 CERT: pratica NoSQL e data processing
- 🔎 RESEARCH: schema validation patterns

**Output:** pipeline ETL con controlli di qualità.

---

## 🕒 Step 14 - Privacy-Aware Text Data Project

**Focus:** analizzare dati testuali sensibili con attenzione a privacy e qualità.

**Competenze**

- Analisi di testi clinici
- PII detection
- Redaction
- Privacy note
- Data quality

**Badge**

- 🟦 MASTER: progetto analisi cartelle cliniche
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-SEC - PII detection and redaction
- 🔎 RESEARCH: Presidio e PII handling

**Output:** report con data quality e note privacy, senza PII nel repository.

---

## 🕒 Step 15 - LLM Fundamentals + Foundation Models

**Focus:** comprendere come funzionano i foundation model e come sceglierli.

**Competenze**

- Tokenization
- Transformer
- Attention e KV cache
- Scaling laws
- SFT, RLHF, DPO
- Costi, performance e licensing
- Benchmarking

**Badge**

- 🟦 MASTER: Large Language Models
- 🟩 DATACAMP: uso API come supporto pratico
- 🟨 CERT: CERT-FM - transformer, attention, scaling, post-training
- 🔎 RESEARCH: Chinchilla, RLHF explained, lm-eval-harness

**Output:** LLM Decision Guide e notebook di benchmark.

---

## 🕒 Step 15.5 - Fine-tuning & Model Adaptation

**Focus:** adattare modelli pre-trained a task specifici.

**Competenze**

- PEFT
- LoRA e QLoRA
- Distillation
- Model merging
- Multi-task fine-tuning
- Valutazione pre/post fine-tuning

**Badge**

- 🟦 MASTER: progetti avanzati
- 🟩 DATACAMP: non specifico
- 🟨 CERT: CERT-FT - PEFT, LoRA, distillation, merging
- 🔎 RESEARCH: Hugging Face PEFT, mergekit, Axolotl

**Output:** notebook LoRA su task custom con metriche comparative.

---

## 🕒 Step 16 - OpenAI API Hands-on

**Focus:** costruire applicazioni pratiche basate su API LLM.

**Competenze**

- API basics
- Chat e conversazioni
- Rate limits
- Retry e idempotency
- Logging richieste

**Badge**

- 🟦 MASTER: concetti da LLM
- 🟩 DATACAMP: introduzione API OpenAI
- 🟨 CERT: consolidamento foundation models hands-on
- 🔎 RESEARCH: rate limits, retries, idempotency

**Output:** mini app LLM con logging e gestione errori.

---

## 🕒 Step 17 - Prompt Engineering Professionale

**Focus:** progettare, testare e tracciare prompt in modo sistematico.

**Competenze**

- Zero-shot e few-shot
- In-context learning
- Prompt injection
- Prompt tracking
- A/B testing
- Failure cases

**Badge**

- 🟦 MASTER: supporto da LLM
- 🟩 DATACAMP: Prompt Engineering
- 🟨 CERT: CERT-PE + CERT-SEC
- 🔎 RESEARCH: promptfoo, Langfuse, injection patterns

**Output:** prompt catalog con report A/B e test di sicurezza.

---

## 🕒 Step 18 - Q&A Application Project

**Focus:** costruire una piccola applicazione Q&A end-to-end.

**Competenze**

- Prompting applicativo
- Caching
- Quality checks
- README riproducibile

**Badge**

- 🟦 MASTER: non applicabile
- 🟩 DATACAMP: progetto Q&A
- 🟨 CERT: consolidamento prompt engineering
- 🔎 RESEARCH: caching prompts/responses

**Output:** mini repository con demo riproducibile.

---

## 🕒 Step 19 - Embeddings + Semantic Search

**Focus:** costruire ricerca semantica misurabile.

**Competenze**

- Embeddings
- Similarity search
- BM25 vs dense retrieval
- Hybrid search
- Recall@k e MRR

**Badge**

- 🟦 MASTER: supporto da LLM
- 🟩 DATACAMP: Embeddings
- 🟨 CERT: CERT-RAG + CERT-EVAL
- 🔎 RESEARCH: reciprocal rank fusion e embedding evaluation

**Output:** retriever v1 con metriche base e confronto dense/hybrid.

---

## 🕒 Step 20 - Vector DB + RAG Base

**Focus:** costruire un sistema RAG iniziale con retrieval controllato.

**Competenze**

- Vector database
- Chunking strategies
- Reranking
- Query expansion
- Context construction
- Evaluation set minimo

**Badge**

- 🟦 MASTER: RAG in LLM o Agentic AI
- 🟩 DATACAMP: Pinecone
- 🟨 CERT: CERT-RAG + CERT-APP
- 🔎 RESEARCH: chunking, reranking, HyDE

**Output:** portfolio RAG skeleton con A/B test su strategie di chunking.

---

## 🕒 Step 21 - LangChain, Agents + RAG

**Focus:** costruire agenti con tool, memoria, retrieval e guardrail.

**Competenze**

- Chains
- Agents
- Tool integration
- Memory systems
- ReAct e planning
- Guardrails
- Agent evaluation

**Badge**

- 🟦 MASTER: Agentic AI
- 🟩 DATACAMP: LangChain
- 🟨 CERT: CERT-AGT
- 🔎 RESEARCH: LangGraph, tool error handling, agent benchmarks

**Output:** agent con due tool, memoria, guardrail e metriche di valutazione.

---

## 🕒 Step 22 - Production, LLMOps + Inference Optimization

**Focus:** prepararsi a portare sistemi AI/LLM in produzione.

**Competenze**

- Architetture applicative LLM
- Function calling
- Model routing
- Caching
- Orchestrazione asincrona
- Quantization
- Batching
- KV cache
- Automated evaluation
- LLM-as-judge
- Hallucination, toxicity e bias testing
- Prompt injection mitigation
- PII redaction
- Secure sandboxing
- GDPR, AI Act e AI ethics
- Feedback loops e human-in-the-loop

**Badge**

- 🟦 MASTER: DevOps e ciclo di vita
- 🟩 DATACAMP: Preparing AI apps for production + LLMOps
- 🟨 CERT: CERT-INF, CERT-APP, CERT-EVAL, CERT-SEC, CERT-FB
- 🔎 RESEARCH: vLLM, secrets management, monitoring, EU AI Act

**Output:** production readiness kit con runbook, dashboard, security checklist, eval plan e inference report.

---

## 🕒 Step 23 - AI/ML Interview Prep

**Focus:** trasformare studio e progetti in risposte tecniche da colloquio.

**Competenze**

- ML fundamentals
- Probabilità e statistica
- LLM, RAG, fine-tuning e inference
- Python framework: scikit-learn, pandas, NumPy, PyTorch
- Data engineering per AI
- System design AI/LLM
- Trade-off e comunicazione tecnica

**Badge**

- 🟦 MASTER: ripasso finale dei moduli AI, LLM, Agentic AI, DevOps
- 🟩 DATACAMP: ripasso mirato ML/LLM/API/RAG/LLMOps
- 🟨 CERT: consolidamento finale delle competenze AI Engineering
- 🔎 RESEARCH: ML interview, LLM system design, RAG evaluation interview

**Output:** flashcard, gap list, mock interview e risposte system design.

---

## Portfolio Target

| Portfolio | Output | Area |
| --------- | ------ | ---- |
| #1 | ML text classification project | Machine Learning |
| #2 | Dockerized ML API | ML Engineering |
| #3 | RAG system with retrieval evaluation | LLM/RAG |
| #4 | Agent with tools, memory and guardrails | Agentic AI |
| #5 | Production readiness kit | LLMOps |

## Skills Coverage

| Area | Coverage |
| ---- | -------- |
| Software Engineering | Python, Git, testing, CI/CD, API design |
| Math Foundations | Statistics, linear algebra, calculus |
| Machine Learning | Baselines, metrics, tuning, error analysis |
| Dataset Engineering | Data quality, annotation, augmentation |
| Data Engineering | SQL, NoSQL, ETL |
| Foundation Models | Transformers, scaling laws, fine-tuning |
| Prompt Engineering | Prompt design, testing, tracking, defense |
| RAG Systems | Embeddings, vector DB, chunking, retrieval eval |
| Agent Systems | Tools, memory, planning, guardrails |
| Production AI | Docker, monitoring, LLMOps, inference optimization |
| Security & Privacy | PII, prompt injection, GDPR, AI ethics |
| Interview Readiness | ML/LLM/system design communication |

## LinkedIn Summary

Sto costruendo una roadmap personale da AI Engineer basata su progetti, non solo su teoria.

Il percorso copre software engineering, machine learning, dataset engineering, LLM, fine-tuning, prompt engineering, RAG, agenti AI, LLMOps, sicurezza e preparazione ai colloqui tecnici.

Repository pubblico:
https://github.com/AlessandroSfratta/ai-engineer-roadmap

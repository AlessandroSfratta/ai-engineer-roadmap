# ROADMAP AI ENGINEER COMPLETA (25 Step + Extra)

> **Versione Potenziata** — Integra ProfessionAI Master + DataCamp + AI Engineering Skills Checklist (gratitudedriven.com)

Legenda badge:

- 🟦 **MASTER**: modulo/progetto dove cercarlo
- 🟩 **DATACAMP**: corso/capitolo dove cercarlo
- 🟨 **CERT**: competenza AI Engineering — TAG automatico, dettagli in [`cert-checklist.md`](./cert-checklist.md)
- 🔎 **INTERNET**: se non lo trovi né nel master né in datacamp
- 🆕 **SKILLS**: dalla AI Engineering Skills Checklist

⏳ = in corso
✅ = completata
🕒 = da iniziare / pianificata

---

## 🤖 ISTRUZIONI PER L'AGENTE AI

> **Quando l'utente chiede "qual è il prossimo step?" o invoca la roadmap, segui questo protocollo:**

### Protocollo di lettura

1. **Trova lo Step ⏳ (in corso)** — è lo step attivo su cui l'utente sta lavorando.
2. **Dentro lo step ⏳, leggi la sezione "Badge" dall'alto verso il basso**, seguendo quest'ordine fisso:
   1. 🟦 **MASTER** (corso del master ProfessionAI)
   2. 🟩 **DATACAMP** (corso/capitolo DataCamp)
   3. 🟨 **CERT** (competency certificazione)
   4. 🔎 **INTERNET** (risorse esterne da cercare)
3. **Il primo badge SENZA ✅ accanto è il prossimo punto da fare.**
   - Se un badge ha `✅` → è completato, passa al successivo.
   - Se un badge ha `_(non specifico)_` o `_(non nel programma)_` → non è applicabile, salta al successivo.
   - **🟨 CERT è un TAG, non un'azione.** Non va "studiato" separatamente. Si completa automaticamente quando lo Step è completato. L'agente deve aggiornare il file `cert-checklist.md` con `[x]` sulle voci corrispondenti e dare un breve riepilogo delle competenze acquisite.
   - Se un badge NON ha `✅` e NON è "non applicabile" → **QUESTO È IL PROSSIMO PUNTO.**
4. **Se TUTTI i badge sono completati o non applicabili**, il prossimo punto è:
   - **Deliverable** → costruire il progetto/output richiesto.
   - **Check** → verificare i criteri di qualità.
5. **Se anche Deliverable e Check sono completati**, contrassegna lo Step come `✅`, poi passa al primo Step `🕒` e cambialo in `⏳`.

### Esempio pratico (Step 2 attuale)

```
Badge dello Step 2:
- 🟦 MASTER: ✅ Programmazione con Python   → ✅ fatto, SKIP
- 🟩 DATACAMP: _(non specifico)_            → non applicabile, SKIP
- 🟨 CERT: CERT-SWE (Python, DSA)           → TAG, non azione, SKIP
- 🔎 INTERNET: "DSA for ML engineers"       → ❌ nessun ✅ → PROSSIMO PUNTO!

Risposta corretta: "Il tuo prossimo punto è studiare DSA for ML engineers (Internet)"
```

### Regole aggiuntive

- **Quando l'utente conferma di aver completato un punto**, aggiungi `✅` accanto al badge corrispondente.
- **Quando aggiorni un badge**, ricalcola se servono meno giorni per lo step e aggiorna la scadenza a cascata.
- **Non saltare mai avanti di Step** senza che tutti i punti dello Step corrente siano completati.

---

## ✅ Step 1 — Setup + Colab + Workflow Pro | ⏰ Scadenza: 20/03/2026

**Obiettivo:** ambiente pronto "da AI engineer" (repo standard, colab, toolchain)

**Argomenti**

- Setup Python env, Colab, repo template
- Git base (branch, commit, README), lint/format
- 🆕 **Linux & command-line tools** — navigazione, scripting bash, ssh basics
- 🆕 **Understanding of numerical precision formats** — float16 vs float32 vs bfloat16

**Badge**

- 🟦 MASTER: **Guida Completa a Google Colab** + (se serve) **Introduzione al pensiero computazionale**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: ✅ **CERT-SWE** → numerical precision, Linux, Git _(vedi cert-checklist.md)_
- 🔎 INTERNET: "poetry vs venv", "pre-commit", "git flow basics", "bash scripting for ML" ✅

**Deliverable:** repo "ai-foundations" con `Makefile`/script setup + README
**Check qualità:** da macchina pulita → install + run ok

---

## ✅ Step 2 — Python Core (fluido) | ⏰ Scadenza: 18/04/2026 | 📅 3 giorni (12h)

**Argomenti**

- funzioni, I/O, exceptions, moduli base
- 🆕 **Data structures and algorithms fundamentals** — complessità Big-O, liste, dizionari, set, code, stack

**Badge**

- 🟦 MASTER: ✅ **Programmazione con Python**
- 🟩 DATACAMP: _(non specifico nel programma)_
- 🟨 CERT: ✅ **CERT-SWE** → Python programming, DSA fundamentals _(vedi cert-checklist.md)_
- 🔎 INTERNET: ✅ "Python best practices project structure", "DSA for ML engineers"

**Deliverable:** mini CLI tool (argparse)
**Check:** input invalidi gestiti + log base

---

## ✅ Step 3 — OOP + Moduli + Typing | ⏰ Scadenza: 22/04/2026 | 📅 4 giorni (16h)

**Argomenti**

- classi, dataclass, typing, struttura modulo

**Badge**

- 🟦 MASTER: ✅ **Programmazione con Python**
- 🟩 DATACAMP: ✅ **Software Engineering e scienza dei dati → Scrivere un modulo Python / Utilizzo delle classi**
- 🟨 CERT: ✅ **CERT-SWE** → Python avanzato (OOP, typing, moduli) _(vedi cert-checklist.md)_
- 🔎 INTERNET: ✅ "typing (mypy) quickstart" (se vuoi typing più serio)

**Deliverable:** package installabile (`pip install -e .`)
**Check:** docstring + typing base

✅ PRIMA DI ANDARE AVANTI SVOLGERE ESAME SU PROFESSIONAI = Progetto: Un algoritmo di correzione per un motore di ricerca

Un Algoritmo di Correzione per un Motore di Ricerca
Caso d'Uso Aziendale: Searchify
Introduzione all'Azienda
Searchify è una startup innovativa che offre un motore di ricerca personalizzato per aziende di medie dimensioni, consentendo di cercare informazioni specifiche nei loro database interni. Uno dei principali vantaggi di Searchify è la semplicità d'uso: gli utenti possono trovare rapidamente documenti, report e altre risorse aziendali digitando parole chiave. Tuttavia, l'azienda si trova ad affrontare un problema che mina l'esperienza dell'utente.

Problema
Il problema principale di Searchify è che molti utenti commettono errori di digitazione durante l'inserimento delle parole chiave. Questi errori causano risultati di ricerca nulli o non pertinenti, portando a insoddisfazione tra gli utenti. Ad esempio, se un utente cerca "raporto vendite 2023" invece di "rapporto vendite 2023", il motore di ricerca non restituisce alcun risultato.

Obiettivo del Progetto
L'obiettivo è sviluppare un algoritmo di correzione automatica per il motore di ricerca di Searchify. Questo algoritmo dovrà:

Rilevare automaticamente gli errori di digitazione o le parole non valide.
Suggerire la parola corretta più probabile.
Restituire risultati pertinenti basati sulla correzione suggerita.
L'implementazione di questa funzionalità migliorerà notevolmente l'esperienza utente, aumentando l'efficienza del motore di ricerca e la soddisfazione dei clienti.

Benefici Attesi
Miglioramento dell'accuratezza: Riduzione degli errori di ricerca dovuti a digitazioni errate.
Incremento della produttività: Gli utenti troveranno le informazioni più velocemente.
Aumento della fedeltà dei clienti: Un'esperienza utente più fluida e soddisfacente porterà a una maggiore adozione del prodotto.
Specifiche del Progetto
Input: Una stringa rappresentante una query di ricerca, digitata dall'utente.
Output:
Se la query contiene errori, il sistema suggerisce una correzione.
Se la query è corretta, restituisce la stessa query.
Funzionalità Chiave:
Confronto tra la parola inserita e un dizionario di parole corrette (da predefinire nel codice).
Implementazione di un algoritmo che calcoli la "distanza di edit" (es. distanza di Levenshtein) per trovare le parole più simili.
Gestione di casi d'uso realistici come errori di battitura comuni, lettere scambiate, omissioni o aggiunte.
Consegna
Scrivi un programma Python che implementi l'algoritmo di correzione automatica per il motore di ricerca. Il tuo codice deve:

Contenere una funzione principale chiamata suggest_correction(query, dictionary).

Parametri:
query: La stringa di input inserita dall'utente.
dictionary: Una lista di parole corrette.
Ritorno:
La parola corretta più probabile o la query originale se è già valida.
Testare il funzionamento con almeno 10 casi d'uso (inclusi errori comuni e query corrette).

Essere ben documentato, con commenti che spieghino le principali scelte implementative.

Fornire un dizionario base contenente almeno 50 parole.

Nota
Il progetto deve essere completato senza l'uso di librerie esterne per il calcolo della distanza di edit o per altre funzionalità. L'obiettivo è che lo studente implementi l'algoritmo interamente da zero.

Modalità di consegna:
Link pubblico a notebook di Google Colab

---

## ⏳ Step 4 — Testing + Manutenibilità | ⏰ Scadenza: 25/04/2026 | 📅 3 giorni (12h)

**Argomenti**

- pytest, logging, refactor, CI

**Badge**

- 🟦 MASTER: **Coding avanzato con Python**
- 🟩 DATACAMP: **Software Engineering e scienza dei dati → Manutenibilità**
- 🟨 CERT: **CERT-SWE** → Testing (pytest, CI/CD) _(vedi cert-checklist.md)_
- 🔎 INTERNET: "GitHub Actions pytest cache"

**Deliverable:** CI verde + coverage ≥70%
**Check:** test riproducibili

---

## 🕒 Step 5 — Reliability (error handling, retry, qualità) | ⏰ Scadenza: 28/04/2026 | 📅 3 giorni (12h)

**Argomenti**

- gestione errori, retry/backoff, qualità "prod"

**Badge**

- 🟦 MASTER: **Coding avanzato con Python**
- 🟩 DATACAMP: (parte "manutenibilità" se utile)
- 🟨 CERT: _(nessun CERT diretto — consolida SWE)_
- 🔎 INTERNET: "timeouts/retries best practices"

**Deliverable:** libreria con logging strutturato + error taxonomy
**Check:** fail-safe (non crasha)

---

## 🕒 Step 6 — ML Baseline + Math Foundations | ⏰ Scadenza: 06/05/2026 | 📅 8 giorni (32h) ⚠️ PESANTE

**Argomenti**

- split, metriche, baseline, pipeline semplice
- 🆕 **Basic statistics and probability** — distribuzioni, Bayes, test ipotesi
- 🆕 **Basic linear algebra** — vettori, matrici, eigenvalues (per capire embeddings/transformers)
- 🆕 **Basic calculus** — derivate, gradiente (per capire backpropagation)

**Badge**

- 🟦 MASTER: **A.I. Applicata per sviluppatori**
- 🟩 DATACAMP: _(non nel programma DataCamp che hai incollato)_
- 🟨 CERT: **CERT-SWE** → stats, linalg, calculus + **CERT-ML** → supervised, metrics, splits _(vedi cert-checklist.md)_
- 🔎 INTERNET: "train/val/test split + leakage examples", "3Blue1Brown Linear Algebra", "StatQuest ML statistics"

**Deliverable:** notebook baseline + report metriche + cheat sheet math
**Check:** seed fisso + risultati ripetibili

---

## 🕒 Step 7 — ML Improvement (tuning + eval) | ⏰ Scadenza: 11/05/2026 | 📅 5 giorni (20h)

**Argomenti**

- preprocessing, feature eng, hyperparam tuning, error analysis
- 🆕 **Understanding common algorithms at high level** — trees, SVM, clustering
- 🆕 **Bias-variance tradeoff** — overfitting/underfitting detection

**Badge**

- 🟦 MASTER: **A.I. Applicata per sviluppatori**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: **CERT-ML** → algorithms, overfitting/underfitting _(vedi cert-checklist.md)_
- 🔎 INTERNET: "cross validation + ablation"

**Deliverable:** **Portfolio #1 v1**
**Check:** confronto baseline→best spiegato

---

## 🕒 Step 7.5 — Dataset Engineering | ⏰ Scadenza: 15/05/2026 | 📅 4 giorni (16h)

**Obiettivo:** saper creare, curare e scalare dataset di qualità per training/fine-tuning

**Argomenti**

- 🆕 **Data acquisition strategies** — web scraping, API, synthetic data generation
- 🆕 **Data quality assessment** — completezza, consistenza, accuratezza, freshness
- 🆕 **Data processing pipelines** — cleaning, normalization, deduplication
- 🆕 **Annotation guidelines creation** — inter-annotator agreement, label studio
- 🆕 **Data augmentation and synthesis** — NLP augmentation, paraphrasing, backtranslation

**Badge**

- 🟦 MASTER: _(non specifico — applica nei progetti)_
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: **CERT-DS** → tutti (acquisition, quality, processing, annotation, augmentation) _(vedi cert-checklist.md)_
- 🔎 INTERNET: "snorkel labeling functions", "label studio tutorial", "synthetic data generation LLM"

**Deliverable:** pipeline dataset con quality report automatico
**Check:** script riproducibile per dataset creation

---

## 🕒 Step 8 — Progetto Master ML: Language ID (museo) | ⏰ Scadenza: 18/05/2026 | 📅 3 giorni (12h)

**Argomenti**

- testo, classificazione lingua, eval

**Badge**

- 🟦 MASTER: **Progetto: identificazione lingua testi per museo**
- 🟩 DATACAMP: (facoltativo: Prompt Eng non serve qui)
- 🟨 CERT: _(nessun CERT diretto — consolida CERT-ML)_
- 🔎 INTERNET: "fastText language identification" (se vuoi benchmark)

**Deliverable:** **Portfolio #1 final** (pulito, README serio)
**Check:** test smoke + riproducibilità

---

## 🕒 Step 9 — REST API per ML (serving) | ⏰ Scadenza: 22/05/2026 | 📅 4 giorni (16h)

**Argomenti**

- FastAPI, contratti, input validation, versioning
- 🆕 **System architecture concepts** — microservices vs monolith, API gateway patterns

**Badge**

- 🟦 MASTER: **Sviluppo di REST API per il Machine Learning**
- 🟩 DATACAMP: **Preparing AI apps for production → Strutturazione end-to-end** (solo se vuoi pattern)
- 🟨 CERT: **CERT-SWE** → API design, system architecture _(vedi cert-checklist.md)_
- 🔎 INTERNET: "pydantic validation patterns", "API versioning strategies"

**Deliverable:** API `/predict` + `/health`
**Check:** test integrazione

---

## 🕒 Step 10 — Progetto Master: Messa in Produzione Language ID | ⏰ Scadenza: 27/05/2026 | 📅 5 giorni (20h)

**Argomenti**

- deploy, packaging, osservabilità minima
- 🆕 **Docker and containers** — Dockerfile optimization, multi-stage builds
- 🆕 **Cloud platforms** — GCP/AWS/Azure basics, compute instances, storage
- 🆕 **Monitoring and logging** — structured logs, metrics, alerting basics

**Badge**

- 🟦 MASTER: **Progetto: Messa in produzione (language ID museo)**
- 🟩 DATACAMP: **Preparing AI apps for production → Best practice produzione**
- 🟨 CERT: **CERT-SWE** → Docker, Cloud, Monitoring _(vedi cert-checklist.md)_
- 🔎 INTERNET: "Docker FastAPI production", "Cloud Run deployment", "Prometheus + Grafana basics"

**Deliverable:** **Portfolio #2 v1** (dockerizzato)
**Check:** healthcheck + logs + metrics endpoint

---

## 🕒 Step 11 — SQL Fundamentals (operativo) | ⏰ Scadenza: 31/05/2026 | 📅 4 giorni (16h)

**Argomenti**

- join, aggregazioni, query analysis

**Badge**

- 🟦 MASTER: **Gestione Database Relazionali con SQL**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: _(nessun CERT diretto — pratica SQL)_
- 🔎 INTERNET: "SQL optimization basics" (se vuoi)

**Deliverable:** report SQL + query documentate
**Check:** query riproducibili

---

## 🕒 Step 12 — Progetto Master SQL: Vendite E-commerce | ⏰ Scadenza: 03/06/2026 | 📅 3 giorni (12h)

**Argomenti**

- analytics, KPI, insight

**Badge**

- 🟦 MASTER: **Progetto: Analisi vendite e-commerce**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: _(nessun CERT diretto — progetto SQL)_
- 🔎 INTERNET: "data storytelling for analytics"

**Deliverable:** report finale + dataset notes
**Check:** definizione KPI chiara

---

## 🕒 Step 13 — NoSQL + Data Processing | ⏰ Scadenza: 07/06/2026 | 📅 4 giorni (16h)

**Argomenti**

- document store mental model, ETL, validation

**Badge**

- 🟦 MASTER: **NoSQL per l'Elaborazione dei Dati**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: _(nessun CERT diretto — pratica NoSQL)_
- 🔎 INTERNET: "schema validation patterns"

**Deliverable:** pipeline ETL + controlli qualità
**Check:** fail cases coperti

---

## 🕒 Step 14 — Progetto Master NoSQL: Cartelle Cliniche | ⏰ Scadenza: 10/06/2026 | 📅 3 giorni (12h)

**Argomenti**

- dati testuali/clinici, structured analysis
- 🆕 **PII detection and redaction** — regex patterns, NER for PII

**Badge**

- 🟦 MASTER: **Progetto: Analisi cartelle cliniche**
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: **CERT-SEC** → PII detection and redaction _(vedi cert-checklist.md)_
- 🔎 INTERNET: "PII handling medical text (basics)", "presidio PII detection"

**Deliverable:** report + data quality + privacy note
**Check:** niente PII nel repo

---

## 🕒 Step 15 — LLM Fundamentals + Foundation Models Deep Dive | ⏰ Scadenza: 19/06/2026 | 📅 9 giorni (36h) ⚠️ PESANTE

**Argomenti**

- tokenization, transformer, tradeoffs, model selection
- 🆕 **Strong deep learning knowledge** — backprop, attention intuition
- 🆕 **Attention mechanism** — self-attention, multi-head, KV cache
- 🆕 **Model scaling laws** — Chinchilla, compute-optimal training
- 🆕 **Post-training techniques** — SFT, RLHF, DPO, ORPO
- 🆕 **Tradeoffs: cost vs performance vs licensing** — $/1M tokens, latency, terms of use
- 🆕 **Open-weight vs open-source vs API models** — Llama, Mistral, GPT, Claude
- 🆕 **Tooling for model benchmarking** — lm-evaluation-harness, HELM, custom evals

**Badge**

- 🟦 MASTER: **Large Language Models**
- 🟩 DATACAMP: _(solo uso API — teoria non prioritaria)_
- 🟨 CERT: **CERT-FM** → tutti (transformer, attention, scaling, post-training, tradeoffs) _(vedi cert-checklist.md)_
- 🔎 INTERNET: "tokenization + context window tradeoffs", "Chinchilla paper", "RLHF explained", "lm-eval-harness tutorial"

**Deliverable:** doc "LLM Decision Guide" (2-3 pagine) + benchmark notebook
**Check:** scelte motivate (costo/perf/licenza) + comparazione pratica

---

## 🕒 Step 15.5 — Fine-tuning & Model Adaptation | ⏰ Scadenza: 24/06/2026 | 📅 5 giorni (20h)

**Obiettivo:** saper adattare modelli pre-trained a task specifici

**Argomenti**

- 🆕 **Parameter-efficient fine-tuning (PEFT)** — perché e quando usarlo
- 🆕 **LoRA and similar approaches** — QLoRA, AdaLoRA, Adapters
- 🆕 **Model distillation** — knowledge transfer to smaller models
- 🆕 **Model merging** — SLERP, TIES, DARE techniques
- 🆕 **Multi-task fine-tuning** — instruction tuning, task vectors

**Badge**

- 🟦 MASTER: _(opzionale in progetti avanzati)_
- 🟩 DATACAMP: _(non nel programma)_
- 🟨 CERT: **CERT-FT** → tutti (PEFT, LoRA, distillation, merging) _(vedi cert-checklist.md)_
- 🔎 INTERNET: "PEFT HuggingFace", "LoRA from scratch", "mergekit tutorial", "Axolotl fine-tuning"

**Deliverable:** notebook fine-tuning LoRA su task custom + comparison metrics
**Check:** valutazione pre/post fine-tuning documentata

---

## 🕒 Step 16 — OpenAI API (hands-on) | ⏰ Scadenza: 27/06/2026 | 📅 3 giorni (12h)

**Argomenti**

- intro API, prompting, chat, conversazioni

**Badge**

- 🟦 MASTER: (concetti in **Large Language Models**)
- 🟩 DATACAMP: **Introduzione all'API OpenAI → intro / sollecitare / conversazioni**
- 🟨 CERT: _(nessun CERT diretto — consolida CERT-FM hands-on)_
- 🔎 INTERNET: "rate limits, retries, idempotency"

**Deliverable:** mini app OpenAI + logging richieste
**Check:** error handling + timeout

---

## 🕒 Step 17 — Prompt Engineering Serio | ⏰ Scadenza: 01/07/2026 | 📅 4 giorni (16h)

**Argomenti**

- best practices, strategie avanzate, prompt per chatbot/enterprise
- 🆕 **In-context learning techniques** — zero-shot, few-shot, chain-of-thought
- 🆕 **Defensive prompt engineering** — prompt injection detection, jailbreak prevention
- 🆕 **Prompt experimentation and tracking** — versioning prompts, A/B testing

**Badge**

- 🟦 MASTER: (supporto concettuale da **Large Language Models**)
- 🟩 DATACAMP: **Prompt Engineering → best practices / avanzate / enterprise / chatbot**
- 🟨 CERT: **CERT-PE** → tutti (prompts, ICL, defensive, tracking) + **CERT-SEC** → prompt injection _(vedi cert-checklist.md)_
- 🔎 INTERNET: "prompt injection patterns", "promptfoo testing", "langfuse prompt tracking"

**Deliverable:** prompt catalog + A/B report + security test report
**Check:** 10 prompt testati + failure cases + injection attempts blocked

---

## 🕒 Step 18 — DataCamp Project: Q&A Parigi | ⏰ Scadenza: 03/07/2026 | 📅 2 giorni (8h)

**Argomenti**

- applicazione API end-to-end + quality

**Badge**

- 🟦 MASTER: —
- 🟩 DATACAMP: **Progetto: attrazioni turistiche Parigi**
- 🟨 CERT: _(nessun CERT diretto — consolida CERT-PE)_
- 🔎 INTERNET: "caching prompts/responses"

**Deliverable:** mini repo progetto con README
**Check:** demo riproducibile

---

## 🕒 Step 19 — Embeddings + Semantic Search | ⏰ Scadenza: 07/07/2026 | 📅 4 giorni (16h)

**Argomenti**

- cosa sono embeddings, similarity, search
- 🆕 **Evaluation metrics** — BLEU, ROUGE, semantic similarity, functional correctness
- 🆕 **Term-based vs embedding-based retrieval** — BM25 vs dense vectors
- 🆕 **Hybrid search** — combining lexical and semantic approaches

**Badge**

- 🟦 MASTER: (probabile accenno in **Large Language Models**)
- 🟩 DATACAMP: **Embeddings → cosa sono / applicazioni / database vettoriali**
- 🟨 CERT: **CERT-RAG** → embedding, retrieval + **CERT-EVAL** → metrics _(vedi cert-checklist.md)_
- 🔎 INTERNET: "embedding evaluation recall@k", "hybrid search reciprocal rank fusion"

**Deliverable:** retriever v1 + metriche base (recall@k, MRR)
**Check:** recall@k documentato + hybrid vs dense comparison

---

## 🕒 Step 20 — Vector DB (Pinecone) + RAG Base | ⏰ Scadenza: 12/07/2026 | 📅 5 giorni (20h)

**Argomenti**

- indexing, queries, performance, RAG
- 🆕 **Document chunking strategies** — fixed size, semantic, recursive, parent-child
- 🆕 **Retrieval optimization techniques** — reranking, query expansion, HyDE
- 🆕 **Context construction patterns** — how to build the final prompt

**Badge**

- 🟦 MASTER: (RAG possibile in **Agentic AI** o LLM, non garantito)
- 🟩 DATACAMP: **Pinecone → intro / manipolazione / ottimizzazione**
- 🟨 CERT: **CERT-RAG** → vector DB, chunking, optimization + **CERT-APP** → context patterns _(vedi cert-checklist.md)_
- 🔎 INTERNET: "chunking strategies + reranking", "Cohere rerank", "HyDE paper"

**Deliverable:** **Portfolio #3 v1** (RAG skeleton con chunking intelligente)
**Check:** eval set minimo + A/B chunking strategies

---

## 🕒 Step 21 — LangChain: Chains + Agents + RAG | ⏰ Scadenza: 17/07/2026 | 📅 5 giorni (20h)

**Argomenti**

- chains, agents, tool integration, RAG
- 🆕 **Planning techniques** — ReAct, Chain-of-Thought, Tree-of-Thought, Plan-and-Solve
- 🆕 **Memory systems implementation** — conversation memory, entity memory, summary memory
- 🆕 **Agent security and safety guardrails** — tool restrictions, output validation
- 🆕 **Agent evaluation methodologies** — task success rate, tool call accuracy

**Badge**

- 🟦 MASTER: **Agentic AI** (+ progetto assistente finanza)
- 🟩 DATACAMP: **LangChain → intro chatbot / catene e agenti / RAG**
- 🟨 CERT: **CERT-AGT** → tutti (tools, planning, memory, guardrails, eval) _(vedi cert-checklist.md)_
- 🔎 INTERNET: "agent tool error handling patterns", "LangGraph multi-agent", "agent benchmarks"

**Deliverable:** **Portfolio #4 v1** (agent + 2 tools + memory + guardrails)
**Check:** tool failures gestiti + guardrails testati + eval metrics

---

## 🕒 Step 22 — Production + LLMOps + Inference Optimization (MEGA-STEP) | ⏰ Scadenza: 27/07/2026 | 📅 10 giorni (40h) ⚠️ PESANTE

**Obiettivo:** padroneggiare tutto ciò che serve per andare in produzione con sistemi LLM/AI

### 22.A — Application Architecture

**Argomenti**

- app end-to-end, function calling, production best practices
- LLMOps lifecycle (ideazione→dev→ops)
- 🆕 **Context construction patterns** — dynamic context assembly
- 🆕 **Input/output guardrails** — content filtering, format validation
- 🆕 **Model routing and gateways** — load balancing, fallbacks
- 🆕 **Caching architectures** — semantic caching, prompt caching
- 🆕 **Orchestration patterns** — async processing, queue-based architectures

### 22.B — Inference Optimization

**Argomenti**

- 🆕 **Compute vs memory-bound inference** — understanding bottlenecks
- 🆕 **Latency metrics** — TTFT (Time to First Token), TPOT (Time Per Output Token)
- 🆕 **Model compression** — quantization (GPTQ, AWQ, GGUF), pruning, distillation
- 🆕 **Batch vs online inference strategies** — throughput vs latency tradeoffs
- 🆕 **Hardware considerations** — GPU (A100, H100), TPU, memory specs
- 🆕 **Batching techniques** — continuous batching, dynamic batching
- 🆕 **Parallel inference strategies** — tensor parallelism, pipeline parallelism
- 🆕 **Caching implementations** — KV cache, prefix caching

### 22.C — Evaluation & Testing

**Argomenti**

- 🆕 **Model evaluation pipelines** — automated eval, regression testing
- 🆕 **Metrics** — perplexity, BLEU, ROUGE, semantic similarity, functional correctness
- 🆕 **Using AI judges and human evals** — LLM-as-judge, RLHF data collection
- 🆕 **Measuring hallucinations, toxicity, bias** — TruthfulQA, ToxiGen, bias benchmarks

### 22.D — Security, Privacy & Ethics

**Argomenti**

- 🆕 **Prompt injection detection/mitigation** — input sanitization, canary tokens
- 🆕 **Adversarial input handling** — jailbreak detection, content moderation
- 🆕 **PII detection and redaction** — presidio, regex patterns, NER-based
- 🆕 **Secure sandboxing** — code execution safety, tool call restrictions
- 🆕 **Model privacy risks** — memorization attacks, data leakage, training data extraction
- 🆕 **Legal compliance** — GDPR, copyright implications, AI Act (EU)
- 🆕 **AI Ethics considerations** — fairness, transparency, accountability

### 22.E — User Feedback Integration

**Argomenti**

- 🆕 **Feedback system design** — thumbs up/down, ratings, free text
- 🆕 **Explicit vs implicit feedback collection** — direct vs behavioral signals
- 🆕 **Data flywheels** — using feedback to improve models
- 🆕 **Human-in-the-loop approaches** — HITL for edge cases, active learning
- 🆕 **Continuous improvement cycles** — monitoring→feedback→retrain loop

**Badge per tutto Step 22**

- 🟦 MASTER: **DevOps e ciclo di vita** + (opz) progetto deploy/monitor sentiment
- 🟩 DATACAMP:
  - **Preparing AI apps for production → Strutturazione / Function calling / Best practice**
  - **LLMOps → ideazione / sviluppo / operativa**
  - **Progetto: estrazione dati strutturati da trascrizioni mediche**

- 🟨 CERT: **CERT-INF** + **CERT-APP** + **CERT-EVAL** + **CERT-SEC** + **CERT-FB** → tutti i rimanenti _(vedi cert-checklist.md)_
- 🔎 INTERNET: "PII redaction pipeline", "secure secrets management", "vLLM deployment", "LangSmith monitoring", "EU AI Act compliance"

**Deliverable:** "Exam Kit" completo:

- Runbook produzione
- Mock exam + gap-fix plan
- Security checklist
- Inference optimization report
- Monitoring dashboard

**Check:** readiness checklist ≥90%

---

## 🕒 Step 23 — AI/ML Interview Prep + Mock Interview | ⏰ Scadenza: 31/07/2026 | 📅 4 giorni (16h)

**Obiettivo:** trasformare tutta la roadmap in risposte da colloquio chiare, tecniche e applicabili a casi reali.

**Argomenti**

- Ripasso strutturato di ML fundamentals, metriche, bias-varianza, regolarizzazione e validazione
- Ripasso di probabilità, statistica, informazione, test di ipotesi e formule essenziali
- Ripasso LLM: Transformer, attention, fine-tuning, RAG, RLHF, LoRA, inference e valutazione
- Framework Python: PyTorch, scikit-learn, pandas, NumPy e training/evaluation loop
- Data Engineering per AI: leakage, pipeline dati, quality checks, feature store, batch vs streaming
- Simulazione colloquio: risposte in 2-4 minuti, esempi pratici, trade-off e follow-up tecnici

**Badge**

- 🟦 MASTER: ripasso finale di **A.I. Applicata per sviluppatori**, **Large Language Models**, **Agentic AI**, **DevOps e ciclo di vita**
- 🟩 DATACAMP: ripasso mirato di ML/LLM/API/Prompt/RAG/LLMOps già completati
- 🟨 CERT: consolidamento finale **CERT-SWE**, **CERT-ML**, **CERT-FM**, **CERT-RAG**, **CERT-EVAL**, **CERT-INF**, **CERT-APP**, **CERT-SEC**
- 🔎 INTERNET: "ML interview questions", "LLM system design interview", "AI engineer mock interview", "RAG evaluation interview questions"

**File di studio:** [`ai-ml-interview-prep-guide.md`](./ai-ml-interview-prep-guide.md)

**Deliverable:** flashcard complete + gap list + 2 mock interview registrate/trascritte + risposta system design AI/LLM.
**Check:** risposte tecniche da 2-4 minuti con definizione, intuizione, trade-off, esempio e collegamento a produzione.

---

# EXTRA (master) — dove mettere gli altri progetti senza rompere la linearità

- **Progetto: algoritmo correzione motore di ricerca** → aggancialo a Settimane **6–7** (Portfolio #1)
- **Progetto: sincronizzare file tra cartelle** → aggancialo a Settimane **4–5** (SWE)
- **Progetto: meeting transcript (summary + tasks)** → aggancialo a Settimane **15–17** (LLM + prompting)
- **Progetto: sintesi cartelle cliniche con HF** → aggancialo tra **19–22** (RAG/LLMOps) oppure come "Fase 9" post-esame
- **MERN su Vercel** → solo se ti serve una UI per demo (nice-to-have)

---

# 📊 Riepilogo Skills Coverage

| Area                   | Step       | Coverage                                    |
| ---------------------- | ---------- | ------------------------------------------- |
| Software Engineering   | 1-5        | ✅ Python, Git, Testing, CI/CD, Docker      |
| Math Foundations       | 6          | ✅ Stats, Linear Algebra, Calculus          |
| ML Basics              | 6-8        | ✅ Supervised/Unsupervised, Metrics, Tuning |
| Dataset Engineering    | 7.5        | ✅ Data Quality, Annotation, Augmentation   |
| Data Engineering       | 11-14      | ✅ SQL, NoSQL, ETL                          |
| Foundation Models      | 15, 15.5   | ✅ Transformers, Scaling Laws, Fine-tuning  |
| Prompt Engineering     | 17         | ✅ Best Practices, Defense, Tracking        |
| RAG Systems            | 19-20      | ✅ Embeddings, Vector DB, Chunking          |
| Agent Systems          | 21         | ✅ Planning, Memory, Guardrails             |
| Inference Optimization | 22         | ✅ Quantization, Batching, Caching          |
| Evaluation & Testing   | 22-23      | ✅ Metrics, AI Judges, Bias Detection, Mock Interview |
| Security/Privacy       | 14, 17, 22 | ✅ PII, Injection, GDPR, Ethics             |
| LLMOps                 | 22         | ✅ Monitoring, Feedback, CI/CD              |
| Interview Readiness    | 23         | ✅ ML/LLM/Stats/Data Engineering interview prep |

---

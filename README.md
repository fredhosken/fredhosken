# Fred Hosken

**Music researcher working at the intersection of computational methods, NLP, and human perception.**

I study *groove* — the quality in music that makes people move — focusing on how musicians create and manipulate subtle timing differences to produce distinct "feels." My work brings together empirical music research, Bayesian inference, corpus linguistics, and retrieval-augmented generation to ask: *what exactly is happening when music feels right?*

Previously: Northwestern (PhD, Music Theory & Cognition), Oxford (MSt), King's College London.  
Currently: Assistant Professor at Butler University; open to research collaborations and industry opportunities.

---

## Featured Projects

### ModernDrummerGPT
**A domain-grounded RAG system for querying the discourse of musicians**

Constructed a retrieval-augmented LLM over four decades of *Modern Drummer* magazine — building a system that embodies the norms, terminology, and debates of a specialist discourse community. Unlike general-purpose LLMs, responses synthesize how musicians themselves have defined contested terms like "groove," "pocket," and "feel" as those definitions evolved across 40+ years of publication.

- Domain-specific corpus ingestion and chunking strategy
- Retrieval pipeline tuned for nuanced, context-dependent musical concepts
- Demonstrates RAG as a tool for preserving *emic* (insider) knowledge — applicable to any specialist corpus

`RAG` `LLM` `corpus linguistics` `NLP` `music information retrieval`

---

### AI Stem Separation & MIR: Validity Assessment
**Bayesian evaluation of AI audio separation tools for onset timing analysis**

Empirically assessed whether AI stem separation tools (used widely in Music Information Retrieval research) introduce timing errors large enough to invalidate downstream analyses. Used Dynamic Time Warping to align onset times from original and AI-separated stems, then applied Bayesian inference to quantify the probability that both represent the same underlying events.

- More musically meaningful than standard SDR/SNR metrics
- Provides a reusable validation framework for any MIR pipeline relying on AI-separated audio
- In review at *Empirical Musicology Review*; invited talk at Vienna (2024)

`Bayesian inference` `Dynamic Time Warping` `signal processing` `MIR` `Python`

---

### Drum Groove Corpora
**Open dataset of drum recordings and onset timing data**

International collaboration (Butler, Lucerne University of Applied Sciences and Arts) producing a structured, open-access repository of drum performance data with annotated onset times. Designed for reproducibility and reuse across empirical music research.

- Published in *Empirical Musicology Review* (special issue on open science)
- Supports corpus-level timing analysis, groove modeling, and MIR benchmarking

`corpus construction` `open data` `music information retrieval` `collaborative research`

---

## Methods & Tools

```
Statistical:    Bayesian inference (posterior estimation, credible intervals)
                Frequentist (mixed-effects models, significance testing)
                Dynamic Time Warping (DTW)

NLP / ML:       Retrieval-Augmented Generation (RAG)
                Corpus linguistics
                Embedding & vector search

Music / Audio:  Music Information Retrieval (MIR)
                Onset detection & timing analysis
                AI stem separation (Demucs, Spleeter, etc.)

Data:           Corpus construction & annotation
                Open science / reproducible research workflows
```

---

## Selected Publications

- **AI Stem Separation & MIR** *(In Review, Empirical Musicology Review)* — Bayesian validity assessment of AI audio tools for timing research
- **Drum Groove Corpora** — *Empirical Musicology Review*, 16(1), 2021 — Open dataset for groove and MIR research
- **The Subjective, Human Experience of Groove** — *Psychology of Music*, 48(2), 2020 — Phenomenological study of groove perception
- **AI Stem Separation Tools in the Aural Skills Classroom** *(In Press, Journal of Music Theory Pedagogy)*

---

## Research Interests

Groove and microtiming · Music perception and cognition · Music Information Retrieval · Corpus methods · NLP applied to music discourse · Bayesian modeling · Performance analysis · Human–AI interaction in music

---

📧 hoskenf@hotmail.com &nbsp;&bull;|&nbsp;  [LinkedIn](https://www.linkedin.com/in/fred-hosken/) &nbsp;&bull;|&nbsp; 🎓 [Google Scholar](https://scholar.google.com/citations?user=1BlgvPYAAAAJ&hl=en)

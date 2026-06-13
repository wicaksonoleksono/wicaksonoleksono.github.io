---
layout: default
---

## About Me

<img class="profile-picture" src="face.jpg">

Hi! I'm Wicaksono Leksono Muhamad, an AI/ML Engineer, NLP Researcher, and Data Scientist. I build LLM systems end to end: agentic workflows, RAG pipelines, and models squeezed onto edge hardware. Most of it came out of cross-university work, deployed for real users in healthcare, education, and climate policy, with first-author publications at ACL venues.

## Summary

AI/ML engineer and researcher. Three years writing production software, plus four spent building and shipping AI systems and data science software that real people use. First-author on three ACL-venue NLP papers (SemEval-2026, BEA 2026). I build LLM systems end to end: agentic workflows, RAG pipelines, models squeezed onto edge hardware. Most of it came out of cross-university work, deployed for users in healthcare, education, and climate policy.

## Education

**Universitas Gadjah Mada** - Yogyakarta, Indonesia

Master of Artificial Intelligence, Feb 2024 - Oct 2025

**Institut Teknologi Sepuluh Nopember** - Surabaya, Indonesia

B.A.Sc. Computational and Applied Mathematics, Aug 2018 - Nov 2022

## Selected Publications

1. **ITLC at SemEval-2026 Task 11: Normalization and Deterministic Parsing for Formal Reasoning in LLMs** - First Author (Mantera Studio), SemEval-2026 (ACL) ([arXiv:2603.02676](https://arxiv.org/abs/2603.02676)). Top-5 across all subtasks via deterministic parsing and structural abstraction of syllogisms into canonical logical forms, outperforming fine-tuning and activation-level baselines.

2. **Improving Lexical Difficulty Prediction with Context-Aligned Contrastive Learning and Ridge Ensembling** - First Author (Mantera Studio), BEA 2026 Shared Task (ACL) ([arXiv:2605.08950](https://arxiv.org/abs/2605.08950)). Ridge ensemble over XLM-RoBERTa and mDeBERTa with ordinal soft contrastive learning; top-15 across all L1 groups (14th Spanish, 11th German, 7th Mandarin).

3. **Aligning Implied Statements for Implicit Hate Speech Generalizability** - First Author, under review (ACL ARR) ([OpenReview](https://openreview.net/pdf?id=pgwGGyy77k)). Triplet contrastive learning with context-bounded semi-hard negatives; +4-8% out-of-domain F1 across three benchmarks.

4. **On-Edge Device Optimization Using Multiple Classification Method for a Cat and Dog Audio Classifier** - First Author, IEEE ([IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10933173/)). 95.2% accuracy, 3 ms latency, 3.8 KB memory on Arduino Nano 33 BLE.

5. **Enhancing Automated User Story Quality Assessment with Large Language Models** - Co-author, ICODSE 2025 ([IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11351886)). Extended automated QUS analysis with LLM-assisted pragmatic and semantic checks.

## Experience

**Researcher and Lead Software Engineer** - Mantera Studio Research Lab (PT. BSM), Jakarta (Feb 2022 - Present)

- Published first-author at SemEval-2026 Task 11, finishing top-5 across all subtasks on multilingual formal reasoning via deterministic parsing and structural abstraction of syllogisms into canonical logical forms.
- Published first-author at BEA 2026 Shared Task, ranking top-15 across all L1 groups (14th Spanish, 11th German, 7th Mandarin) with a Ridge ensemble over XLM-RoBERTa and mDeBERTa using ordinal soft contrastive learning.
- Lead engineering across the lab's production AI portfolio, directing system architecture and shipping customer-facing LLM applications in collaboration with Queen's University Belfast, UGM, and Deakin University.

**Research Assistant, Machine Learning Systems** - Universitas Gadjah Mada, Yogyakarta (Feb 2026 - Present)

- Develop early-exit training and inference methods for energy-efficient, low-latency model deployment on resource-constrained edge hardware (NVIDIA Jetson Orin) across 7W-25W power budgets.

**Research Assistant, Software Engineering Lab** - Universitas Gadjah Mada, Yogyakarta (Mar 2025 - Oct 2025)

- Led the ML workstream for a national grant: delivered PHQ-aligned LLM screening with deep-learning facial affect analysis, evaluated on 302 samples, and presented results to university stakeholders and grant reviewers.
- Built LLM-based NLP tooling for requirements engineering, adding pragmatic and semantic quality checks for user-story specifications that extended prior automated QUS analysis.

**Web Developer** - Mastej Studio, Malang (2019 - 2022)

- Built and shipped [What's On Malang](https://whatsonmalang.com), a React/Vite tourism platform (400+ DAU, 100 leads/day), and the [Begawan apartment](https://www.begawan-apartment.com/) marketing site with 360-degree virtual tours (10 daily inquiries).
- Co-developed [Janur](https://janur.wedding/), a digital wedding-invitation site with built-in attendance tracking; built 7 custom invitations.
- Helped run [Pasar Santai](https://pasarsantai.themastej.com/), an annual local market event in Malang, as logistics officer and web developer.

## Projects

- [Dyslexic Reader](https://dyslexic.app) (Mantera Studio x UGM x Queen's University Belfast) - Dart, Next.js, Kubernetes, Python, gRPC, webhook. LLM-powered dyslexia support app deployed on Kubernetes with Dart mobile and Next.js web frontends; real-time font-rendering dyslexia lens, LLM summarization and text-professionalization, and an AHRQ-aligned screening protocol.
- [Mental Health Screening Platform](https://mentalhealth.laptopmerahputih.id) (Mantera Studio) - Flask, LangGraph, LangChain, PyTorch, webhook, LiteRT. LLM-driven PHQ + CPAS screening workflows with LangGraph agentic orchestration serving 40+ concurrent sessions; deep-learning facial affect capture, with p95 latency and serving cost cut 90% via local response batching and request queuing, monitored with LangSmith.
- RAG Chatbots: [TASYA](https://tasya.dtmiugm.id/) & [IndoClimate](https://chat.indoclimate.id) (Mantera Studio x UGM, Deakin) - Flask, React, ChromaDB, LangGraph. WhatsApp webhook and REST RAG services over institutional docs and Indonesian climate legislation; ~2,000 pages across 7 documents indexed into ChromaDB, multi-step retrieval and generation via LangGraph, traced with LangSmith.
- **SOC Dashboard** (Mantera Studio, under NDA) - Vite, Redux Toolkit, Go, LangGraph, LangSmith. Refactored frontend to domain-driven design, cutting redundant code 70%; integrated server telemetry ingestion, distributed tracing, audit logging, and LLM-based log summarization.
- [Sijinak Attendance System](https://github.com/airlanggawicaksono/sijinak_win) (Mantera Studio) - gRPC, FFI, Dart, Python, C. RFID-based attendance system integrating Hikvision hardware via FFI to a native C SDK; microservice layer over gRPC with a Dart frontend.

## Skills

**Programming Languages:** Python, TypeScript/JavaScript, Go, Dart, Java, C/C++, Rust, SQL (PostgreSQL)

**ML & NLP:** PyTorch, TensorFlow, HuggingFace Transformers, scikit-learn, fine-tuning, contrastive learning, knowledge distillation, model optimization, embeddings, multilingual NLP, mechanistic interpretability

**LLM & Agentic AI:** LangGraph, LangChain, LangSmith, Model Context Protocol (MCP), retrieval-augmented generation (RAG), prompt engineering, OpenAI API, ChromaDB, agentic workflows

**Web & Backend:** React, Next.js, Flask, Node.js, Vite, REST API, gRPC, microservices, API gateways

**Infrastructure & Observability:** Docker, Kubernetes, Git, Linux, nginx, Google Cloud Platform, CI/CD, distributed tracing, logging, audit logging, LaTeX

**Data Science:** Pandas, NumPy, Matplotlib, data analysis, data visualization, experiment tracking

**Languages:** Indonesian (Native), English (Professional - TOEFL ITP 587), German (B1), Javanese (Conversational)

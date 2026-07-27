<h1 align="center">Hi, I'm Sampreeth 👋</h1>

<p align="center">
  <em>AI Engineer · Applied ML · NYU '25 · Occasional filmmaker</em>
</p>

<p align="center">
  <a href="https://sampreethavvari.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-sampreethavvari.github.io-111?style=for-the-badge&logo=astro&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/sampreethavvari/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:spa9659@nyu.edu"><img alt="Email" src="https://img.shields.io/badge/Email-spa9659%40nyu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.instagram.com/sampreeth.sharma/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>

---

### About

I'm an AI Engineer at **Hybridge Implants** in New York. I turn fuzzy, real-world business problems — operations, pricing, medical imaging, clinical QA — into shipped systems that survive real users.

I completed my **MS in Computer Engineering at NYU** in May 2025 (3.9 GPA), and spent earlier years building backend audio analytics at **Shure** and enterprise AI infrastructure at **Optimal Living Systems**. I care about clarity, good taste, and tech that feels human.

---

### What I'm shipping in 2026

```
┌─────────────────────────────────────────────────────────────────────────┐
│ 🦷  CBCT Scan Validator              Production medical-imaging AI       │
│     Replaced a $98K + $26K/yr vendor quote with an in-house stack        │
│     running < $50/mo on GCP. Closes a 10-year recurring scan-loss        │
│     problem with a 13-class taxonomy, OpenVINO inference on Cloud Run,   │
│     CICT-gated CI/CD, and a tag-based release pipeline.                  │
│                                                                          │
│ 💰  Treatment Estimator              Per-location frozen-pricing engine  │
│     Decoupled a decade-old single-price tool into a code-driven          │
│     decision tree + DB-driven price catalog. Write-once *_at_capture     │
│     columns enforced by Postgres triggers make the 6-month price         │
│     guarantee a real system property — not a sticker on the PDF.         │
│                                                                          │
│ 📊  Cowork Dashboard                 Single source of truth, two clinics │
│     Pivoted from a brittle live-API dashboard to a weekly-Excel          │
│     pipeline. Patient↔lead linkage jumped 49% → 99% via Monday's         │
│     connect column. Six tabs sharing one metrics module — structurally   │
│     impossible for two views to disagree on the same number.             │
│                                                                          │
│ 🧠  Doc Coach (Consultation QA)      Zoom → Gemini → coaching reports    │
│     Multi-tenant Cloud Run pipeline scoring every implant consultation   │
│     against a 7-criterion clinical framework. JSON-Schema-validated      │
│     Gemini output, three-layer identity resolution, color-coded PDFs.    │
│     +130% treatment acceptance, +43% revenue, -35% hallucinations.       │
└─────────────────────────────────────────────────────────────────────────┘
```

More detail (with architecture diagrams and project narratives) on the [portfolio site](https://sampreethavvari.github.io).

---

### Selected earlier work

- **Loan Radar** · production-grade loan default scoring with MLflow lineage, Docker + Ray + Kubernetes, 0.79ms median inference at 33k+ samples/s
- **LLM Persuasion (NYU research)** · SFT + RLHF (GRPO/PPO) with QLoRA + TRL on Llama 3.1, comparing reward-modeled policy-optimization variants
- **Fake News & Sentiment** · fine-tuned Llama 3 8B + RoBERTa on 1.8M tweets; 76% on LIAR; LDA topic-level patterns
- **ResNet under 5M params** · custom CIFAR-10 architectures; 97.12% on ResNet-26 with <5M parameters

---

### Tech I reach for

**Languages** Python · TypeScript · Go · Java · SQL  
**Web / Backend** FastAPI · Next.js · Auth.js · Drizzle · Flask · Spring Boot · Node.js  
**ML / Data** PyTorch · PyTorch Lightning · MONAI · Transformers · TRL · OpenVINO · pgvector · LangChain  
**Infra / Cloud** GCP (Cloud Run · Cloud SQL · Eventarc · Pub/Sub · Vertex AI) · AWS (S3 · ECS · EC2) · Docker · Kubernetes · Terraform · GitHub Actions  
**Observability** OpenTelemetry · Cloud Logging · W&B · MLflow · pino · structlog

---

### How I think about engineering

- **Brainstorm → ADR → spec → plan → execute.** Tradeoff tables and consequences live in the repo, not in someone's head.
- **Single source of truth, always.** If two tabs can disagree, they will.
- **Trust internal code; validate at boundaries.** Don't pad with defensive checks for things that can't happen.
- **Honest evaluation over green dashboards.** Ship the honest AUROC number; don't game the gate.
- **Boring tech where it serves the user.** Apps Script + weekly Excel beats a real-time dashboard nobody trusts.

---

### Off-keyboard

I make movies — screenplay writer, editor, director. Currently editing one. Happy to chat about story structure as much as system design.

<p align="center">
  <sub>📍 New York, NY · 📬 <a href="mailto:savvari@hybridgeimplants.com">savvari@hybridgeimplants.com</a> · 🌐 <a href="https://sampreethavvari.github.io">sampreethavvari.github.io</a></sub>
</p>

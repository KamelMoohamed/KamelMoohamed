# Kamel Kamel

**Software Engineer · AI Product Engineering**
TypeScript · Python · AWS — I ship production LLM features and the evaluation systems that keep them reliable.

📍 Melbourne, Australia · Full unrestricted Australian work rights · Available now
[Portfolio](#) · [LinkedIn](https://linkedin.com/in/YOUR-HANDLE) · [Email](mailto:kamel.zaghloul01@gmail.com)

---

## What I build

**Production LLM systems.** Structured extraction and classification with schema-constrained
output, confidence thresholds, and human-in-the-loop fallback when the model isn't sure. Shipped
inside a real product with real billing, not a demo.

**Multi-tenant SaaS on AWS.** ECS Fargate, Lambda, SQS, RDS in isolated subnets, KMS-encrypted
S3, WAF — provisioned with Terraform, deployed through CI, covered by Vitest, Jest and Playwright.

**Evaluation and red-teaming for AI systems.** My research is adversarial machine learning: I
design attacks against models, build the benchmarking harnesses that measure them, and publish
the defences. I apply the same discipline to LLM applications — golden sets, adversarial suites,
and CI gates that block a quality regression from reaching production.

---

## Currently

🔨 **CliniDoc (public edition)** — de-identified, deployable build of a multi-tenant clinical
document platform: multi-channel ingestion (HL7/FHIR, SFTP, email, fax), a Claude extraction
pipeline traced end-to-end with OpenTelemetry, Terraform infrastructure, and a live demo tenant.

🔨 **Agent harness** — a multi-step LLM agent platform with durable execution on Step Functions,
idempotent tool calls, human approval gates on irreversible actions, and an evaluation suite
wired into CI as a deploy gate: golden datasets, LLM-as-judge calibrated against human labels,
and an adversarial prompt-injection suite.

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **CliniDoc** | Multi-tenant clinical document automation SaaS, built solo end to end | NestJS · Prisma · PostgreSQL · Next.js · Claude API · Terraform · AWS · Stripe |
| **ArtisanHub** | Multi-language, multi-currency Shopify marketplace — storefront, embedded admin, Functions and Flow | TypeScript monorepo · Next.js · Remix · Shopify GraphQL |
| **Football Match 3D Reconstruction** | Real-time 3D reconstruction from monocular video; fine-tuned mesh recovery to <50mm MPJPE | Python · Unity · Computer Vision |

---

## Research

**Voice authentication security · adversarial ML · anti-spoofing** — MSc by Research, Deakin University

- *Rethinking Targeted Data Poisoning in Voice Authentication: A Critique and Defense Mechanism*
  — **IEEE Internet of Things Journal**, 2026
- *Spectral Masking and Interpolation Attack (SMIA): A Black-box Adversarial Attack against Voice
  Authentication and Anti-Spoofing Systems* — **Interspeech 2026** (accepted)
- *A Survey of Threats Against Voice Authentication and Anti-Spoofing Systems* — under review, Q1 journal

🏆 NASA Space Apps Challenge — 1st Place Cairo (2022, 2023), Global Finalist Honorable Mention

---

## Stack

`TypeScript` `Python` `Node.js` `NestJS` `React` `Next.js` `PostgreSQL` `pgvector`
`AWS` `Terraform` `Docker` `GitHub Actions` `OpenTelemetry`
`Claude API` `OpenAI API` `RAG` `AI Agents` `MCP` `LangChain` `PyTorch`

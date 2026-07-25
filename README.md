<!--
  GitHub profile README for github.com/KamelMoohamed
  Copy this file to the KamelMoohamed/KamelMoohamed repo as README.md (that special repo
  renders on your profile page). Strip this comment block first.
-->

<h1 align="center">Hi 👋, I'm Kamel</h1>
<h3 align="center">AI &amp; Software Engineer — LLM products · production backend · adversarial ML research</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/kamelkamel/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:kamel.zaghloul01@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://orcid.org/0009-0008-5645-4390"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
</p>

---

I build AI systems that survive contact with production, and I break them for a living in
research. The two feed each other: attacking voice authentication models for my MSc makes me
sceptical of anything that only looks good on a validation split, and that scepticism is what
shapes the products I ship.

- 🌍 Based in **Geelong / Melbourne, Australia** — full Australian work rights
- 🎓 **MSc by Research**, School of IT, **Deakin University** — thesis submitted 2026
- 🔬 Researching **adversarial attacks against voice authentication** — 2 accepted papers, 1 survey under review
- 🏥 Building **ClinicDoc** — an AI document automation SaaS for medical clinics, solo
- 🎓 **BSc Systems & Biomedical Engineering**, Cairo University — GPA 3.8/4.0
- 📫 **kamel.zaghloul01@gmail.com**
- 💬 Open to AI/ML and backend engineering roles, and to research collaboration

---

### 🚀 What I'm building

**🏥 ClinicDoc — AI document automation for medical clinics** *(solo, 2026)*
Clinical documents arrive by fax, email, HL7/FHIR or SFTP; Claude extracts the fields and
classifies urgency; patients are matched with fuzzy + phonetic matching; the document is filed
straight into the clinic's practice management system. Six PMS adapters, Stripe credit billing,
TOTP MFA, OIDC SSO, AWS in Terraform. Demo on request.
`NestJS` `Prisma` `PostgreSQL` `Next.js 14` `Claude API` `Terraform` `AWS ECS Fargate`

**🛍️ [ArtisanHub](https://github.com/KamelMoohamed/artisanhub) — international multi-vendor Shopify marketplace**
Next.js 14 storefront across three markets with RTL Arabic, an embedded Remix vendor dashboard,
four Shopify Functions compiled to Wasm, three Flow workflows.
→ **[Live storefront](https://artisanhub.vercel.app)**
`TypeScript` `Next.js 14` `Remix` `Polaris` `Shopify Functions`

---

### 🔬 Research

My MSc programme at Deakin, on the security of voice authentication systems.

| Paper | Venue | Status |
|---|---|---|
| [Rethinking Targeted Data Poisoning in Voice Authentication: A Critique and Defense Mechanism](https://doi.org/10.1109/JIOT.2026.3673716) | IEEE Internet of Things Journal | Published 2026 |
| [Spectral Masking and Interpolation Attack (SMIA)](https://arxiv.org/abs/2509.07677) | Interspeech 2026 | Accepted |
| [A Survey of Threats Against Voice Authentication and Anti-Spoofing Systems](https://arxiv.org/abs/2508.16843) | Q1 journal | Under review |

**SMIA** is a black-box attack that hides adversarial perturbation in frequency regions humans
cannot hear — audio that sounds authentic to a listener but carries a payload the model can't
ignore. Up to **100% success against standalone anti-spoofing countermeasures** and **97.5%
against voice authentication**, outperforming prior work.

---

### 🧠 Selected ML work

- **🔬 [Ovarian cancer subtype classification](https://github.com/KamelMoohamed/UBC-OCEAN)** — dual-model histopathology system pairing supervised classification with zero-shot anomaly detection for the outlier class. **98.74% accuracy** across five subtypes. *(UBC-OCEAN)*
- **⚽ Football match 3D reconstruction** — monocular broadcast footage → full 3D animated reconstruction. Camera calibration from pitch markings, multi-player tracking through occlusion, 3D mesh recovery fine-tuned to **<50 mm MPJPE**. *BSc graduation project with CyShield — code not public.*
- **🌪️ [Carrington event prediction](https://github.com/KamelMoohamed/DISCOVER-DSCOVR)** — forecasting geomagnetic storms 24h ahead from raw NASA DSCOVR telemetry. Transformer to extend the signal, BERT-derived encoder fine-tuned for Kp index prediction. *NASA Space Apps winner.*
- **🧠 [3D brain tumour segmentation](https://github.com/KamelMoohamed/3D-Brain-Tumor-Segmentation)** — volumetric medical image segmentation. `PyTorch` `MONAI`
- **🚗 License plate detection** — OCR-driven vehicle plate recognition at **95% accuracy**.
- **🎛️ [Frequalizer](https://github.com/KamelMoohamed/Equalizer)** — signal equaliser with five modes, including ECG arrhythmia isolation and voice tone shifting.

---

### 🏆 Awards

- 🥇 **NASA Space Apps Challenge** — 1st Place & Best Use of AI *(Cairo, 2023)*
- 🥇 **NASA Space Apps Challenge** — 1st Place & Best Space Solution *(Cairo, 2022)*
- 🌍 **Global Finalist Honourable Mention**, worldwide *(2022)*
- 🚀 Awarded a **NASA camp at NASA HQ & Houston Space Center**, USA *(2024)*
- 🥉 **STP Mackathon 3.0** — 3rd Place

---

### 🛠️ Tech

**Languages** — `TypeScript` `Python` `JavaScript` `C++` `C#` `Java` `SQL`

**LLM & GenAI** — `Claude API` `OpenAI` `Gemini` `LangChain` `AutoGen` `RAG` `Vector DBs` `MCP` `n8n`

**ML** — `PyTorch` `TensorFlow` `scikit-learn` `MONAI` `Adversarial ML` `Computer Vision` `Speech`

**Backend** — `NestJS` `Node.js` `Express` `FastAPI` `Prisma` `REST` `GraphQL` `Stripe`

**Frontend** — `React` `Next.js 14` `Remix` `Tailwind` `Unity` `Qt`

**Cloud & DevOps** — `AWS (ECS, Lambda, SQS, RDS, CDK, WAF, KMS)` `Terraform` `Azure` `Docker` `GitHub Actions`

**Databases** — `PostgreSQL` `MySQL` `MongoDB`

---

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=KamelMoohamed&theme=tokyonight&hide_border=true" height="160" alt="Contribution streak"/>
</p>

<!--
  Deliberately omitted: github-readme-stats.vercel.app (the "top languages" / "stats" cards).
  The public instance is heavily rate-limited and was returning 503 when this was written, which
  shows up as a broken image on your profile. If you want those cards back, deploy your own
  instance (it's a one-click Vercel deploy from anuraghazra/github-readme-stats) and point the
  URLs at it — self-hosted, they're reliable.

  Your old README also used badges.pufler.dev, github-readme-streak-stats.herokuapp.com and
  activity-graph.herokuapp.com. All three are dead — Heroku ended free dynos — so they were
  rendering as broken images. streak-stats.demolab.com above is the maintained replacement.
-->


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=KamelMoohamed&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

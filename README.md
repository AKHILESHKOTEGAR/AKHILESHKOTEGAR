<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,50:8B5CF6,100:A855F7&height=200&section=header&text=%3C%20Akhilesh%20Bhaskar%20Kotegar%20%2F%3E&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=console.log(%22building%20things%20that%20actually%20ship%22)&descSize=16&descAlignY=58&fontDesc=Fira%20Code" />

<!-- coder typing animation -->
<a href="https://github.com/AKHILESHKOTEGAR">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=A855F7&center=true&vCenter=true&width=700&height=60&lines=%24+whoami+--verbose;Full-Stack+Engineer+%7C%7C+AI+Builder;git+commit+-m+%22ship+it%22+%F0%9F%9A%80;while(alive)+%7B+code();+learn();+repeat();+%7D" alt="Typing animation" />
</a>

<img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" alt="Coder gif" width="320" />

<br/><br/>

<img src="https://img.shields.io/badge/M.Sc._Applied_CS-TH_Deggendorf-6366F1?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=1e1b4b" />
<img src="https://img.shields.io/badge/📍_Deggendorf-Germany-8B5CF6?style=for-the-badge&labelColor=1e1b4b" />

<br/>

<a href="https://akhilesh-kotegar-portfolio.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-A855F7?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1e1b4b" />
</a>
<a href="https://www.linkedin.com/in/akhileshkotegar/">
  <img src="https://img.shields.io/badge/LinkedIn-6366F1?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1e1b4b" />
</a>
<a href="mailto:akhilkotegar@gmail.com">
  <img src="https://img.shields.io/badge/Email-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1e1b4b" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=AKHILESHKOTEGAR&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/AKHILESHKOTEGAR?style=for-the-badge&color=6366F1&labelColor=1e1b4b&label=FOLLOWERS" />

</div>

---

## ⚡ About Me

```typescript
const akhilesh = {
  role: "Full-Stack & AI Engineer",
  currently: "M.Sc. Applied Computer Science @ TH Deggendorf 🇩🇪",
  background: "2.5+ years building travel-tech products end-to-end",
  loves: ["real-time systems", "RAG pipelines", "clean architecture"],
  funFact: "won a national hackathon at 24h with 3 hours of sleep",
  openTo: ["Working Student", "Internships", "Junior SWE / AI roles"],
};
```

I build software that survives contact with real users. Started as an intern at a travel-tech startup where I ended up owning features across the whole stack — frontend, backend, auth, cloud, CI/CD. These days I'm deep into applied AI: retrieval systems that cite their sources, ML pipelines that degrade gracefully instead of crashing, and real-time dashboards that stay smooth at 60fps.

Currently in Germany doing my master's, learning German (A2 → B1 in progress), and shipping side projects that solve actual problems — from F1 race replays to fraud-proof inventory audits.

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,python,cpp,java,kotlin&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,vue,angular,tailwind,html,css&theme=dark" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,graphql,redis,postgres,mysql,mongodb,prisma&theme=dark" />

**Cloud & DevOps**

<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,kubernetes,git,gitlab,jenkins,postman,figma&theme=dark" />

**AI / ML**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" />

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/RAG_Pipelines-8B5CF6?style=for-the-badge" />
<img src="https://img.shields.io/badge/ChromaDB-A855F7?style=for-the-badge" />
<img src="https://img.shields.io/badge/ONNX_Runtime-6366F1?style=for-the-badge&logo=onnx&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini_%2F_Claude_%2F_OpenAI-7C3AED?style=for-the-badge" />

</div>

---

## 🧠 AI / ML Focus Areas

| Domain | Level | What I've actually done with it |
| :--- | :---: | :--- |
| **RAG & Retrieval** | 🟣🟣🟣🟣🟣 | Hybrid search (dense + BM25), RRF fusion, cross-encoder re-ranking, citation resolution |
| **LLM Applications** | 🟣🟣🟣🟣🟣 | Search-grounded generation, multi-tier fallback pipelines, structured outputs |
| **Model Deployment** | 🟣🟣🟣🟣⚪ | ONNX inference without PyTorch deps — cut memory and latency for production |
| **Applied ML** | 🟣🟣🟣🟣⚪ | Online learning with `partial_fit`, scikit-learn classifiers, OCR pipelines |
| **Deep Learning** | 🟣🟣🟣⚪⚪ | Self-supervised + contrastive learning, transformer embeddings, LSTM — thesis work |

---

## 🚀 Projects

<details open>
<summary><b>🏁 &nbsp;Pitwall — F1 Telemetry & Race Replay Platform</b></summary>
<br/>

Ever wanted to rewatch a full F1 race with live positions for all 20 cars, telemetry charts, and lap-by-lap comparisons? That's Pitwall. It replays any session from **1950 to 2026** — race, quali, or sprint.

The fun engineering problem: source telemetry only updates at **10fps**, which looks choppy. Instead of reaching for WebGL, I pre-render ~10,000 interpolated frames per race with NumPy, stream them over **Server-Sent Events** from FastAPI, and let a 90ms CSS transition smooth everything to a buttery **60fps** in the browser. Sometimes the boring tool is the right tool.

| | |
| :--- | :--- |
| **Stack** | Next.js 15 · React Three Fiber · FastAPI · FastF1 · NumPy · Pandas |
| **Highlights** | 3D car viewer with team-colour lighting · live speed/DRS/gear/tyre data · in-memory cache so multi-hundred-MB sessions never reprocess |
| **Deployed** | Frontend on Vercel · Dockerized backend on Railway |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

<details>
<summary><b>🔎 &nbsp;Synapse-Query — RAG That Cites Its Sources</b></summary>
<br/>

A retrieval system for technical documents that answers questions **with citations** instead of confident guesses. Built because most RAG demos fall apart the moment you feed them a real-world PDF with tables, scans, and weird formatting.

Retrieval runs two ways at once — dense vectors (ChromaDB) and classic BM25 keyword search — then merges results with **Reciprocal Rank Fusion** and re-ranks with a cross-encoder. When a PDF turns out to be a scan, an automated **Tesseract OCR fallback** kicks in so ingestion never silently fails.

The production touch: models run on **ONNX Runtime** instead of full PyTorch, which slashed memory usage and inference latency. It's the difference between "works on my machine" and "works on a cheap server."

| | |
| :--- | :--- |
| **Stack** | Python · ChromaDB · BM25 · Cross-Encoder · ONNX Runtime · Tesseract |
| **Highlights** | Hybrid retrieval + RRF · citation-resolution logic · OCR fallback ingestion |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

<details>
<summary><b>🍾 &nbsp;Liquor Inventory System — Audit Software Built Like a Threat Model</b></summary>
<br/>

Inventory fraud has a simple recipe: staff see the expected count before scanning, then "find" exactly that number. So I built a **blind audit scanner** — auditors scan without ever seeing what the system expects. No target, no manipulation.

Every other feature follows the same paranoid logic. Stock snapshots **freeze** at audit time so numbers can't be edited after the fact. Cross-store injection is blocked so one location can't pad another's count. A 3-tier role system (Owner → Manager → Staff) runs on JWT with **JTI-based token revocation**, so a fired employee's session dies instantly. The output: auto-generated PDF compliance reports with manager sign-off that hold up in front of government inspectors.

| | |
| :--- | :--- |
| **Stack** | Full-stack · JWT auth · PostgreSQL · mobile scanner |
| **Highlights** | Blind scanning · snapshot freezing · bottle-level discrepancy matrix · real-time dashboard with calendar view |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

<details>
<summary><b>🩺 &nbsp;HealthGuard — Allergy Detection · 🏆 National Hackathon Winner</b></summary>
<br/>

Built in 24 hours, won **1st prize nationally** at HackZion. You tell it your allergies in plain language ("I react to peanuts and most dairy"), point your camera at any product, and it tells you if it's safe — OCR reads the ingredient list and cross-checks it against your profile in real time.

The part I'm proudest of is the **3-tier fail-safe pipeline**: Gemini handles the smart analysis, scikit-learn takes over if the LLM is unavailable, and rule-based logic is the final floor. For something safety-related, "the API is down" can't mean "no answer." Hallucinations get filtered by grounding LLM suggestions against the **Open Food Facts** database, and the ML layer learns from user feedback live via `partial_fit` — no retraining runs needed.

| | |
| :--- | :--- |
| **Stack** | Next.js · TypeScript · Prisma · PostgreSQL · Gemini API · scikit-learn · EasyOCR |
| **Highlights** | LLM → ML → rules graceful degradation · search-grounded answers · real-time online learning |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

<details>
<summary><b>🛰️ &nbsp;Spacecraft Log Anomaly Detection — B.E. Thesis</b></summary>
<br/>

Spacecraft telemetry logs are massive, unlabeled, and hide the anomalies that matter most. My thesis tackled detection **without any labels** — using self-supervised contrastive learning (DBLCL / EnhancedDBLCL) to learn what "normal" looks like, with transformer embeddings + LSTM for sequence context and density-based methods (GMM, Isolation Forest) to flag the outliers.

| | |
| :--- | :--- |
| **Stack** | Python · Transformers · LSTM · GMM · Isolation Forest |
| **Highlights** | Fully unsupervised · contrastive representation learning · high-accuracy detection on raw logs |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

<details>
<summary><b>📦 &nbsp;Barcode Inventory App — Flutter + Serverless AWS</b></summary>
<br/>

A mobile inventory app where scanning a barcode updates stock automatically — built with Flutter/Kotlin on top of MongoDB, with AWS Lambda + API Gateway handling the backend serverlessly. Cut manual stock-entry effort by ~70% and was shaped directly by feedback from the ops team actually using it.

| | |
| :--- | :--- |
| **Stack** | Flutter · Kotlin · MongoDB · AWS Lambda · API Gateway |

🔗 [View repo](https://github.com/AKHILESHKOTEGAR)

</details>

---

## 💼 Experience

### Software Engineer Intern · Celebto Technologies — Bengaluru 🇮🇳
**Nov 2022 – Jul 2025** *(two stints, alongside my bachelor's)*

Joined a travel-tech startup as an intern and ended up owning things interns usually don't touch:

- Built an **itinerary platform** with TypeScript, React, Kotlin and Spring Boot — UX up **35%**, operational efficiency up **30%**
- Designed the **ranking algorithms** behind place & activity discovery, using user preferences and search behaviour
- Extended Google OAuth via **Firebase + Kotlin** to capture custom user data the default flow doesn't give you
- Set up **GCP cloud automation with RBAC** that supported 1.5+ years of product scaling
- Built **Docker-based CI/CD pipelines** that cut deployment errors by **40%**
- Shipped pixel-perfect Next.js components from Figma to production inside sprint cycles

`TypeScript` `React` `Next.js` `Kotlin` `Spring Boot` `Firebase` `GCP` `Docker` `CI/CD` `Agile`

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| 🥇 **1st Prize — HackZion National Hackathon, 2023** | National-level win for HealthGuard — LLM-powered allergy & nutrition platform, built in 24h |
| 🥉 **3rd Prize — Illusive Alphabits, RIT** | Linux & debugging challenge — terminal decoding, error hunting, hidden-code discovery |

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=AKHILESHKOTEGAR&show_icons=true&hide_border=true&title_color=A855F7&icon_color=8B5CF6&text_color=c9d1d9&bg_color=0d1117&count_private=true&include_all_commits=true" />
<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=AKHILESHKOTEGAR&hide_border=true&background=0d1117&stroke=A855F7&ring=A855F7&fire=8B5CF6&currStreakLabel=A855F7&sideLabels=c9d1d9&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" />

<br/><br/>

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AKHILESHKOTEGAR&layout=compact&hide_border=true&title_color=A855F7&text_color=c9d1d9&bg_color=0d1117&langs_count=10" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=AKHILESHKOTEGAR&theme=onedark&no-frame=true&no-bg=true&margin-w=4&margin-h=4&column=7" />

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=AKHILESHKOTEGAR&bg_color=0d1117&color=A855F7&line=8B5CF6&point=ffffff&area=true&area_color=6366F1&hide_border=true" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AKHILESHKOTEGAR/AKHILESHKOTEGAR/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AKHILESHKOTEGAR/AKHILESHKOTEGAR/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/AKHILESHKOTEGAR/AKHILESHKOTEGAR/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## 🎯 Current Focus

```yaml
learning:
  - distributed systems & software architecture
  - agentic LLM workflows & orchestration
  - german: A2 → B1 (in progress 🇩🇪)

building:
  - real-time, AI-native web applications
  - retrieval systems that cite their sources

exploring:
  - ONNX / quantization / low-latency inference
  - system design at scale

open_to:
  - working student & internship roles (Germany / EU)
  - junior software / AI engineer positions
```

---

## 🤝 Connect

<div align="center">

<a href="mailto:akhilkotegar@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1e1b4b" />
</a>
<a href="https://www.linkedin.com/in/akhileshkotegar/">
  <img src="https://img.shields.io/badge/LinkedIn-6366F1?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1e1b4b" />
</a>
<a href="https://akhilesh-kotegar-portfolio.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-A855F7?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1e1b4b" />
</a>

<br/><br/>

*build → break → learn → repeat*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A855F7,50:8B5CF6,100:6366F1&height=110&section=footer" />

</div>

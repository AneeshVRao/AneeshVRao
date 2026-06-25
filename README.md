<p align="center">
  <img
  src="https://capsule-render.vercel.app/api?type=waving&height=320&color=0:0F172A,25:2563EB,50:7C3AED,75:EC4899,100:F59E0B&text=Aneesh%20Venkatesha%20Rao&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=AI%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20Open%20Source%20Contributor&descAlignY=58&descSize=24&animation=fadeIn&stroke=ffffff&strokeWidth=1"
  width="100%"
/>
</p>


<p align="center">
  <a href="https://github.com/AneeshVRao">
    <img src="https://img.shields.io/badge/GitHub-AneeshVRao-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://linkedin.com/in/aneesh-venkatesha-rao">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="https://aneesh.codes">
    <img src="https://img.shields.io/badge/Portfolio-aneesh.codes-0EA5E9?style=for-the-badge" alt="Portfolio website" />
  </a>
  <a href="mailto:aneeshvrao2017@gmail.com">
    <img src="https://img.shields.io/badge/Email-aneeshvrao2017%40gmail.com-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email contact" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/AneeshVRao?label=Followers&amp;style=for-the-badge&amp;logo=github&amp;color=6366F1&amp;logoColor=white" alt="GitHub followers" />
  <img src="https://img.shields.io/badge/Public_Repos-16-EC4899?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Public repos" />
  <img src="https://img.shields.io/badge/Based_in-Warangal%2C_India-22D3EE?style=for-the-badge&amp;logo=googlemaps&amp;logoColor=white" alt="Location" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=500&amp;size=18&amp;duration=2800&amp;pause=950&amp;color=A78BFA&amp;center=true&amp;vCenter=true&amp;width=950&amp;lines=Designing+AI-native+products+with+production-grade+engineering;Building+full-stack+systems+focused+on+speed%2C+quality%2C+and+scale;Currently+shipping+Stratos+for+the+IBM+AI+Builders+Challenge" alt="Animated summary of engineering focus" />
</p>

<p align="center">
  <a href="#about">About</a> •
  <a href="#currently-building">Currently Building</a> •
  <a href="#featured-builds">Featured Builds</a> •
  <a href="#hardware-engineering">Hardware Engineering</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#github-telemetry">GitHub Telemetry</a> •
  <a href="#achievements">Achievements</a> •
  <a href="#open-to-collaborate">Open To Collaborate</a>
</p>

---

## About

```bash
$ whoami
Aneesh Venkatesha Rao — B.Tech ECE, NIT Warangal (2024–2028)

$ status
Third-year student • SIH 2025 National Finalist (Top 5 of 75,000+ submissions)

$ focus --areas
- AI/ML product engineering (RAG, LLM orchestration, retrieval systems)
- Full-stack application architecture
- Distributed data + automation pipelines
- Human-in-the-loop developer tooling

$ currently
Shipping Stratos for the IBM AI Builders Challenge, while building toward
open-source contributor credit (LFX Mentorship / GSoC).
```

I enjoy bridging research-minded experimentation with production-ready software.
My approach combines **AI/ML capability**, **backend rigor**, and **clean frontend execution** to ship products that are both technically strong and genuinely usable.

---

## Currently Building

<p>
  <img src="https://img.shields.io/badge/IN_PROGRESS-Stratos-F97316?style=for-the-badge&amp;logo=ibm&amp;logoColor=white" alt="Currently building Stratos" />
</p>

**Stratos — "Football, Understood"**

An IBM AI Builders Challenge submission (due June 30, 2026) spanning two tracks: a tactical decision explainer and a multilingual fan companion. Built on **IBM Granite / WatsonX**, **Docling**, **Langflow**, and **Context Forge**, with a **D3.js** frontend backed by a stateless, per-call backend.

**Tech:** IBM Granite, WatsonX, Docling, Langflow, Context Forge, D3.js

🔗 **Repository:** <!-- add repository link here once public -->

---

## Featured Builds

<details open="open">
  <summary><strong>ContextCraft</strong> · AST-aware codebase search engine &#160;<img src="https://img.shields.io/badge/Solo_Build-8B5CF6?style=flat-square" alt="Solo build" /></summary>
  <br />

- Built a hybrid search engine that parses codebases with **tree-sitter** — functions and classes as atomic chunks, never mid-function splits
- Implemented **Reciprocal Rank Fusion** merging pgvector cosine similarity + PostgreSQL BM25, with per-repo RRF normalization for multi-repo queries
- Added **Cohere cross-encoder reranking** (20 → 10 candidates) and 1-hop dependency graph expansion with cycle detection across file boundaries
- Enriched every chunk with **git blame** author metadata; benchmarked at **80% source hit rate** at 3.88s P50 latency across 30 queries
- Published to **PyPI** (`pip install contextcraft-py`); CI enforces mypy strict, ruff, and pytest before every merge
- **Tech:** Python, FastAPI, PostgreSQL, pgvector, tree-sitter, Cohere, Next.js, Docker

🔗 **Repository:** [github.com/AneeshVRao/ContextCraft](https://github.com/AneeshVRao/ContextCraft)

</details>

<details>
  <summary><strong>Humanify</strong> · AI text humanizer — live, monetized SaaS &#160;<img src="https://img.shields.io/badge/Solo_Build-8B5CF6?style=flat-square" alt="Solo build" /></summary>
  <br />

- Built a production SaaS that rewrites AI-generated text to read naturally, with multi-AI routing across Gemini and Claude depending on input characteristics
- Shipped and currently runs a paid Pro tier (₹999/mo) with Razorpay billing integration
- Designed the full subscription lifecycle — auth, billing, plan gating — on Supabase
- **Tech:** Next.js, Supabase, Razorpay, Gemini API, Claude API

🔗 **Repository:** [github.com/AneeshVRao/Humanify](https://github.com/AneeshVRao/Humanify)

</details>

<details>
  <summary><strong>Dev-Saarathi</strong> · Voice-first AI coding assistant &#160;<img src="https://img.shields.io/badge/Team_Project-F59E0B?style=flat-square" alt="Team project" /></summary>
  <br />

- Built a voice-to-code pipeline in **11 Indian languages** through transcription + intent detection
- Designed an AI orchestration flow (Intent Detection → Guardrails → Execution Router) for safe automation of code actions
- Implemented context-aware reasoning over **50+ files / 100k+ characters** via RAG to reduce hallucinated outputs
- Added human approval controls while keeping **3–6s voice-to-response latency**
- **Tech:** TypeScript, Python, AWS (Bedrock, Transcribe, S3), RAG

🔗 **Repository:** [github.com/ashb155/dev-saarathi](https://github.com/ashb155/dev-saarathi) <sub>(team repo, hosted under collaborator's account)</sub>

</details>

<details>
  <summary><strong>ShabdSetu</strong> · AI-powered multilingual learning platform &#160;<img src="https://img.shields.io/badge/Team_Project-F59E0B?style=flat-square" alt="Team project" /></summary>
  <br />

- Built an end-to-end learning system for **10+ Indian languages** using IndicTrans2 + Whisper
- Developed fuzzy pronunciation scoring for real-time speaking feedback
- Engineered layered caching (in-memory + Firestore) for **sub-50ms** response paths
- Added gamification with XP, streaks, and 27 achievements synced across authenticated sessions
- **Tech:** Next.js, React, FastAPI, IndicTrans2, Whisper, Firestore

🔗 **Repository:** [github.com/AneeshVRao/ShabdSetu](https://github.com/AneeshVRao/ShabdSetu)

</details>

<details>
  <summary><strong>Nexus Load Balancer</strong> · HTTP load balancer in Go &#160;<img src="https://img.shields.io/badge/Solo_Build-8B5CF6?style=flat-square" alt="Solo build" /></summary>
  <br />

- Built a lightweight HTTP load balancer from scratch with round-robin request distribution across backend pools
- Implemented active health checks (periodic probing) and passive health checks (live-traffic failure detection) to pull unhealthy backends out of rotation automatically
- **Tech:** Go, net/http

🔗 **Repository:** <!-- add repository link here -->

</details>

---

## Hardware Engineering

Coursework and lab projects at NIT Warangal, several built alongside classmates Akula Sahasra, Adhvay Shrujal, and Arushi Pundir.

**Bayesian In-Memory Compute (IMC) Core**
SRAM-based weight lookup, LFSR-driven stochastic sampling, a Kogge-Stone parallel-prefix popcount unit, and FSM control logic — implemented and verified in Vivado.

**FPGA Brain Tumor Segmentation**
Otsu thresholding + watershed segmentation accelerated via Vitis HLS on a MicroBlaze soft core, achieving a **144–229× speedup** over a software baseline. Deployed on Nexys 4 DDR / Artix-7.

**Tech:** Verilog, Vivado, Vitis HLS, MicroBlaze

---

## Tech Stack

### Languages &amp; Core
<p>
  <img src="https://skillicons.dev/icons?i=python,ts,js,go,cpp,sql" alt="Languages and core technologies" />
</p>

### Frontend &amp; Backend
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,fastapi,tailwind" alt="Frontend and backend stack" />
</p>

#### UI &amp; Data Libraries
<p>
  <img src="https://img.shields.io/badge/-Radix_UI-161618?style=for-the-badge&amp;logo=radixui&amp;logoColor=white" alt="Radix UI" />
  <img src="https://img.shields.io/badge/-TanStack_Query-FF4154?style=for-the-badge&amp;logo=reactquery&amp;logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/-Zod-3E67B1?style=for-the-badge&amp;logo=zod&amp;logoColor=white" alt="Zod" />
  <img src="https://img.shields.io/badge/-Stripe-635BFF?style=for-the-badge&amp;logo=stripe&amp;logoColor=white" alt="Stripe" />
</p>

### AI/ML, Data &amp; Cloud
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,aws,gcp,docker,postgres,firebase" alt="AI ML, data, and cloud stack" />
</p>

#### AI &amp; Database Services
<p>
  <img src="https://img.shields.io/badge/-LangChain-1C3C3C?style=for-the-badge&amp;logo=langchain&amp;logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/-Cohere-9333EA?style=for-the-badge&amp;logo=cohere&amp;logoColor=white" alt="Cohere" />
  <img src="https://img.shields.io/badge/-IBM_Granite_%2F_WatsonX-052FAD?style=for-the-badge&amp;logo=ibm&amp;logoColor=white" alt="IBM Granite and WatsonX" />
  <img src="https://img.shields.io/badge/-Whisper-412991?style=for-the-badge&amp;logo=openai&amp;logoColor=white" alt="Whisper" />
  <img src="https://img.shields.io/badge/-Anthropic-D97757?style=for-the-badge&amp;logo=anthropic&amp;logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/-Supabase-3FCF8E?style=for-the-badge&amp;logo=supabase&amp;logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/-Razorpay-0C2451?style=for-the-badge&amp;logo=razorpay&amp;logoColor=white" alt="Razorpay" />
</p>

### Developer Workflow
<p>
  <img src="https://skillicons.dev/icons?i=git,githubactions,figma,postman,linux" alt="Developer workflow tooling" />
</p>

---

## Engineering Priorities

- Build for **clarity**, then optimize for **scale**
- Treat performance as a core product feature
- Keep architecture modular and maintainable
- Use AI where it delivers measurable utility
- Design developer experiences that reduce friction

---

## GitHub Telemetry

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api?username=AneeshVRao&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=38BDF8&text_color=CBD5E1&count_private=true&include_all_commits=true"
    alt="GitHub Stats"
  />
  <img
    height="170"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=AneeshVRao&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=CBD5E1"
    alt="Top Languages"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com?user=AneeshVRao&hide_border=true&background=0D1117&ring=A78BFA&fire=F472B6&currStreakLabel=E2E8F0&sideNums=CBD5E1&currStreakNum=E2E8F0&sideLabels=94A3B8&dates=64748B"
    alt="GitHub Streak"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=AneeshVRao&bg_color=0D1117&color=CBD5E1&line=38BDF8&point=F472B6&area=true&hide_border=true"
    alt="Contribution Graph"
  />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/AneeshVRao/SnakeAnim/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)"
            srcset="https://raw.githubusercontent.com/AneeshVRao/SnakeAnim/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake"
         src="https://raw.githubusercontent.com/AneeshVRao/SnakeAnim/output/github-contribution-grid-snake-dark.svg">
  </picture>
</p>

---

## Achievements

- 🥇 **Smart India Hackathon 2025 — National Finalist** (Top 5 in problem statement, selected from 75,000+ submissions)
- 📜 **13 professional certifications** across cloud, software engineering, and data science (Google, Meta, IBM)
- 🏅 **65+ Olympiad medals** in national-level Mathematics and Science competitions

---

## Open To Collaborate

- 🌱 Open-source contributions — actively working toward **LFX Mentorship** / **Google Summer of Code**
- 🤖 AI/ML product engineering internships
- 🛠️ Backend / full-stack engineering roles
- 🔗 Collaborations in dev tooling, RAG systems, and developer productivity

<p>
  If you're building something meaningful in AI, full-stack systems, or developer tooling, I'd love to connect.
</p>

<p align="center">
  <a href="mailto:aneeshvrao2017@gmail.com">
    <img src="https://img.shields.io/badge/Reach%20Out-Mail-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email me" />
  </a>
  <a href="https://linkedin.com/in/aneesh-venkatesha-rao">
    <img src="https://img.shields.io/badge/Let%27s%20Connect-LinkedIn-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="Connect on LinkedIn" />
  </a>
  <a href="https://aneesh.codes">
    <img src="https://img.shields.io/badge/Portfolio-aneesh.codes-0EA5E9?style=flat-square" alt="Visit portfolio" />
  </a>
</p>

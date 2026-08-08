<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=AI+Engineer+%7C+Agentic+RAG+%26+Multi-Agent+Systems;Building+LLM-powered+products+that+ship;LangChain+Open+Source+Contributor" alt="Typing SVG" />

### AI Engineer building production-grade agentic RAG systems, multi-agent orchestration, and retrieval pipelines — currently open to AI Engineer roles.

[![Portfolio](https://img.shields.io/badge/Resume-View-1F4E79?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/document/d/1Skgh2fb2qbjXiap_mJDEuWAe4aql9Dnb/edit?usp=sharing&ouid=102555872536251924623&rtpof=true&sd=true)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/soban-shankar-7731b3305/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ssoban2004@gmail.com)

<img src="https://komarev.com/ghpvc/?username=Soban-2004&label=Profile+Views&color=1F4E79&style=flat" alt="Profile Views" />

</div>

---

### GitHub Stats

<div align="center">
<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=Soban-2004&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
<img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Soban-2004&layout=compact&theme=tokyonight&hide_border=true" width="38%" />
</div>

<div align="center">
<img src="https://github-trophies.vercel.app/?username=Soban-2004&theme=tokyonight&no-frame=true&row=1&column=6&margin-w=8&margin-h=8" width="90%" />
</div>

---

### 📊 Impact Snapshot

<div align="center">

| Recruiter funnel narrowed | Report latency cut | Schema scale indexed | Config effort reduced | OSS PR merged |
|:---:|:---:|:---:|:---:|:---:|
| **~95%** fewer full rubric reviews | **4.5s → 1s** via 7 parallel guardrail scanners | **2,000+** HCM tables/views via RAG | **~60–70%** manual effort automated | **`langchain-ai/langchain`** #39238 |

</div>

---

### About Me

I'm an AI Engineer with hands-on enterprise experience through a 6-month internship at **Drivestream**, where I built multi-agent orchestration systems automating Oracle Fusion cloud transformation workflows — plus two production-grade agentic RAG platforms shipped end-to-end, from retrieval architecture to deployment.

I care about the difference between "using an LLM" and building a system that **retrieves grounded evidence, reasons over it, and takes real action** — hybrid search, reranking, guardrails, fallback chains, and evaluation, not just a prompt wrapped in a chatbot.

- 🔭 Currently building agentic AI systems using **LangChain, LangGraph, LlamaIndex, and MCP (Model Context Protocol)**
- 🌱 Deepening expertise in **AI evaluation, prompt engineering, and production LLMOps**
- 🐛 Merged **PR #39238** into [`langchain-ai/langchain`](https://github.com/langchain-ai/langchain) — fixed a data-loss bug in `RecursiveJsonSplitter`
- 📍 Based in Chennai, India — open to relocation (Bengaluru)

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🔍 [AI Resume & Job Matcher — Full-Stack RAG Platform](https://github.com/Soban-2004/Job_Resume_Matcher)**

A dual-mode recruitment platform where job seekers get resume-vs-JD breakdowns and recruiters manage hiring end-to-end.

- Hybrid retrieval — dense + sparse (BM25) fused via reciprocal rank fusion, re-scored with a cross-encoder reranker
- Three-stage recruiter funnel narrows candidates to the top **~5%**, cutting rubric reviews by **~95%**
- Three-tier LLM fallback chain (Ollama → Gemini → Groq) for rate-limit resilience

`Next.js 16` `FastAPI` `Supabase` `Qdrant`

[**Live Demo**](https://ai-resume-job-matcher-rag-platform-soban-2004s-projects.vercel.app/) · [**Source**](https://github.com/Soban-2004/Job_Resume_Matcher)

</td>
<td width="50%" valign="top">

**🤖 [Agentic RAG Customer Support Platform (Flipkart FAQ)](https://github.com/Soban-2004/Flipkart_faq_chatbot)**

An autonomous support agent over a ~2,000-entry FAQ corpus that checks order/refund status and escalates to humans.

- Intent-routing planner + 5 tools (FAQ search + 4 MCP tools) on LlamaIndex
- LiteLLM gateway with fallback across 3 models / 2 providers
- LLM Guard guardrails (7 parallel scanners) cut latency **~4.5s → ~1s**
- Validated via 25-scenario RAGAS evaluation

`LlamaIndex` `MCP` `LiteLLM` `Qdrant` `Docker`

[**Live Demo**](https://agentic-rag-customer-support-platform.onrender.com) · [**Source**](https://github.com/Soban-2004/Flipkart_faq_chatbot)

</td>
</tr>
</table>

---

### Open Source

> **[langchain-ai/langchain #39238](https://github.com/langchain-ai/langchain/pull/39238)** — Fixed a data-loss bug where `RecursiveJsonSplitter.split_json()` silently discarded non-dict top-level input instead of raising an error. Traced the regression to a prior fix, opened [#39192](https://github.com/langchain-ai/langchain/issues/39192), and shipped a merged fix with 9 regression tests covering lists, primitives, `None`, and existing dict behavior — validated against 149 passing tests.

---

### Tech Stack

**LLM & Agentic AI**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-4A4A4A?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Programming & Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Vector DB & Retrieval**
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Weaviate](https://img.shields.io/badge/Weaviate-00C7B7?style=flat-square)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**LLMOps & Evaluation**
![LiteLLM](https://img.shields.io/badge/LiteLLM-6C63FF?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6B6B?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

**Cloud & DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### Certifications

- Oracle Cloud Infrastructure – Agentic AI Certified Foundations Associate
- Oracle Cloud Infrastructure – AI Foundations Associate
- Machine Learning Specialization – Stanford University

---

<div align="center">

**📫 ssoban2004@gmail.com** · **📍 Chennai, India**

</div>

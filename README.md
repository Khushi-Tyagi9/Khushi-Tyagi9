<div align="center">
<img src="banner.svg" width="100%" />
</div>

## Hi there

I'm Khushi, a final-year Computer Science student who enjoys building software that people can depend on. Most of my work has been in backend development, where I like designing APIs, thinking about system architecture, and understanding the trade-offs behind engineering decisions. Along the way, I've explored machine learning and LLM-based systems, but what keeps me interested is building software that's reliable, practical, and easy to improve.

---

## Currently Working On

- Building **LLM Gateway**, a single API layer that unifies access to Groq, OpenAI, Anthropic, and Ollama for client applications
- Exploring backend architecture and machine learning systems
- Learning more about evaluation pipelines, system design, and scalable software

---

## Featured Projects

### [LLM Cost Autopilot](https://github.com/Khushi-Tyagi9/llm-cost-autopilot)

Built to answer a simple question:

> **Can every prompt justify using the most expensive model?**

An intelligent routing system that predicts prompt complexity and selects the most cost-effective LLM while maintaining response quality through selective verification.

**Highlights**
- Reduced inference costs by **79%** across 1,000+ real requests
- Investigated and mitigated a real reliability gap: found a 90% fabrication rate on niche factual queries through repeated testing, then built and validated a targeted routing fix
- Random Forest prompt complexity classifier, 83.88% cross-validated accuracy
- Multi-provider routing engine (Groq, Anthropic, OpenAI)
- Selective LLM verification, response caching, retry-with-backoff
- 94 automated tests, CI-verified on every push
- Dockerized, FastAPI backend

**Tech**
`Python` • `FastAPI` • `Scikit-Learn` • `SQLite` • `Docker`

---

### [Mailwise](https://github.com/Khushi-Tyagi9/mailwise)

An AI-powered email assistant that triages an entire inbox at once: classifies incoming emails, extracts action items, retrieves context from past correspondence using RAG, and drafts replies in the user's own writing style.

**Highlights**
- Bulk inbox processing with a triage view, not one-off drafting
- Eval-driven development: urgency classification improved from 50% to 75% accuracy through prompt iteration against 36 hand-labeled real emails
- Found and fixed a real data bug (mislabeled HTML content corrupting classification) via evaluation testing, not assumption
- Read-only by design: only requests `gmail.readonly`, drafts open in Gmail for the user to send, nothing is sent automatically
- Rate-limit-aware architecture: a rule-based pre-filter catches obvious newsletters/notifications before they reach the LLM

**Tech**
`Python` • `FastAPI` • `Streamlit` • `ChromaDB` • `Groq`

---

## GitHub Activity

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Khushi-Tyagi9&show_icons=true&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Khushi-Tyagi9&hide_border=true" height="165"/>
</div>

---

## Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/khushityagi09)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:khushityagi1008@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=6,11,20&section=footer" width="100%"/>

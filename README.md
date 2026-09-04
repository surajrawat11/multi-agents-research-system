# 🔬 ResearchMind — Multi-Agent AI Research System

<p align="center">
  <b>Research smarter. Search deeper. Write better.</b>
</p>

<p align="center">
  A multi-agent AI research system that searches the web, extracts deeper information,
  generates a structured research report, and critically reviews its own output.
</p>

<p align="center">

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Streamlit-FF4B4B?style=for-the-badge)](https://multi-agents-research-system-rumag3u4mtkbmzyknfwzd6.streamlit.app/)

[![GitHub Repository](https://img.shields.io/badge/💻%20GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/surajrawat11/multi-agents-research-system)

</p>

---

## 🚀 Live Project

### 👉 [Launch ResearchMind](https://multi-agents-research-system-rumag3u4mtkbmzyknfwzd6.streamlit.app/)

Enter any research topic and let the multi-agent pipeline investigate it.

### 💻 [View Source Code on GitHub](https://github.com/surajrawat11/multi-agents-research-system)

---

## 🧠 What is ResearchMind?

**ResearchMind** is an AI-powered multi-agent research system built with Python, LangChain, Groq and Streamlit.

Instead of relying on a single LLM response, the system divides the research process into specialized stages:

```text
                    ┌─────────────────────┐
                    │   Research Topic    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   🔍 Search Agent   │
                    │  Web Research       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   📄 Reader Agent   │
                    │ Deep URL Scraping   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   ✍️ Writer Chain   │
                    │ Research Report     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   🧐 Critic Chain   │
                    │ Review & Score      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Final Research     │
                    │      Report         │
                    └─────────────────────┘

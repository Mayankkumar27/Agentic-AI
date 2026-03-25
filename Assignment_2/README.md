# 🤖 Autonomous Research Agent — LangChain + Groq

**Assignment 2 | Agentic AI (CS-F) | Sharda University**

An AI-powered autonomous agent that researches any topic and generates
a fully structured research report — automatically.

---

## 🧠 What It Does

1. Takes a topic as input
2. Searches the web using DuckDuckGo
3. Fetches knowledge from Wikipedia
4. Summarizes and analyzes using LLaMA3
5. Generates a detailed structured report

---

## 🛠️ Tech Stack

| Component | Tool |
|-----------|------|
| LLM | Groq LLaMA3.3-70B |
| Web Search Tool | DuckDuckGo Search |
| Knowledge Tool | Wikipedia |
| Runtime | Google Colab |
| Language | Python |

---

## 📋 Output Format

- Cover Page
- Title
- Introduction
- Key Findings
- Challenges
- Future Scope
- Conclusion

---

## 🚀 How to Run

**Step 1** — Open `research_agent.ipynb` in Google Colab

**Step 2** — Get free Groq API key at [console.groq.com](https://console.groq.com)

**Step 3** — Paste key in Cell 2:
```python
os.environ["GROQ_API_KEY"] = "your_key_here"
```

**Step 4** — Change topic in Cell 6:
```python
TOPIC = "Impact of AI in Healthcare"
```

**Step 5** — Run all cells → report downloads automatically

---

## 📦 Install
```bash
pip install groq duckduckgo-search wikipedia
```

---



---

## 📄 Sample Outputs

| # | Topic | File |
|---|-------|------|
| 1 | Impact of AI in Healthcare | [View](sample_outputs/Sample_Output_1_AI_in_Healthcare.txt) |
| 2 | Quantum Computing and Cybersecurity | [View](sample_outputs/Sample_Output_2_Quantum_Cybersecurity.txt) |

---

## 👤 Author

**Mayank**
B.Tech CSE — Section F
Sharda School of Engineering & Technology
Sharda University

---

## 📝 License

MIT License

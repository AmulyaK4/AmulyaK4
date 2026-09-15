<div align="center">

# Hey, I'm Amulya 👋
### Full-stack AI tinkerer · RAG pipelines by day · debugging FAISS at midnight

*I ship AI systems instead of admiring them in notebooks.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kokkula-amulya-8176382a5/)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/amulya8)
[![Medium](https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@amulyaakokkula)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=flat-square&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/amulyaakokkula)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:amulyaakokkula@gmail.com)

</div>

---

### 🧬 About Me

IT grad from Hyderabad who'd rather ship a working AI product than polish another notebook nobody runs. I work across the LLM stack end to end - RAG pipelines, vector search, backend APIs — and I don't stop at "it works on my machine." Every project below is **live and clickable**, not a screenshot. If it's broken, that's on production, and I've probably already found the bug before you did.

Fresh off an SDE internship shipping real dashboards on real data — now hunting for the next thing to build (or break, professionally, in a test suite).

🎯 **Currently open to:** AI/ML Engineer · Python Developer · Data Analyst · SDET / Testing roles

---

### ⚡ Currently Shipping

**[🎯 HireMatch AI](https://amulya8-hirematch-ai.hf.space)** — an AI that reads job descriptions so recruiters don't have to
LangChain + Groq (Llama 3.3 70B) rip a JD apart into structured skill requirements, then FAISS + sentence-transformers score how well a resume actually fits — no dumb keyword matching. War story: shipped it, watched every match score come back **0%**, spent an evening convinced the model was broken. Turned out FAISS vectors just needed L2 normalization. One `faiss.normalize_L2()` later, it worked perfectly.
`LangChain` `Groq` `FAISS` `Streamlit` `Docker` → **[Live Demo](https://amulya8-hirematch-ai.hf.space)** · **[Code](https://github.com/AmulyaK4/hirematch-ai)**

**[📄 ResuméLens](https://resumelens-eta.vercel.app)** — makes LLMs stop being poets and start being useful
Real-time ATS scoring, section-by-section feedback, missing-keyword detection. Built solo, end-to-end, on Next.js. The real fight here wasn't the AI — it was forcing an LLM that *loves* to ramble into strict, parseable JSON every single time, via schema validation + re-prompting on malformed output. Zero resumes stored — everything lives in memory and vanishes the second the request ends.
`Next.js` `LangChain` `Groq` → **[Live Demo](https://resumelens-eta.vercel.app)** · **[Code](https://github.com/AmulyaK4/ResumeLens)**

**[👁️ InsightLense](https://github.com/AmulyaK4/InsightLense-Research-Document)** — a RAG bot that actually *looks* at your PDFs
Every other RAG chatbot reads text and pretends the charts don't exist — which is exactly where the real numbers live. InsightLense uses Gemini Vision to interpret figures and diagrams, LlamaParse to keep tables structured instead of scrambled, and a hybrid FAISS + BM25 retriever underneath — so it nails both "what's the trend here?" and "what's the exact number in Figure 8?"
`LangChain` `FAISS` `BM25` `Gemini Vision` `LlamaParse` `FastAPI` → **[Code](https://github.com/AmulyaK4/InsightLense-Research-Document)**

**[📊 Zomato Analytics Dashboard](https://github.com/AmulyaK4/zomato-dashboard)** — 9,000+ restaurants, zero guesswork
Power BI + DAX dig into cuisine trends by city, price-vs-rating correlation, and which neighborhoods are criminally underserved by good food.
`Pandas` `Power BI` `DAX` → **[Code](https://github.com/AmulyaK4/zomato-dashboard)**

<table>
<tr>
<td width="50%">

**🔍 Crime Rate Prediction**
Logistic regression predicting risk by location from historical crime data.
`Python` `scikit-learn` → [Code](https://github.com/AmulyaK4/Crime-Rate-Prediction)

</td>
<td width="50%">

**📧 Email Spam Classifier**
NLP model separating spam from ham, served through Flask.
`Python` `scikit-learn` `Flask` → [Code](https://github.com/AmulyaK4/E-mail-Spam-Classifier)

</td>
</tr>
</table>

---

### 🛠️ The Stack

```yaml
ai_ml:      [LangChain, Groq, FAISS, sentence-transformers, scikit-learn, XGBoost, Prompt Engineering]
backend:    [Python, FastAPI, REST APIs, Docker, Streamlit]
data:       [Pandas, NumPy, PostgreSQL, MySQL, Power BI, DAX, Metabase]
testing:    [Selenium, API Testing, Postman]
languages:  [Python, SQL, JavaScript, Java, C]
tools:      [Git, VS Code, Hugging Face Spaces]
```

---

### 🏆 Trophy Case

| | |
|---|---|
| 🎓 | Oracle Cloud Infrastructure — Generative AI Professional |
| 🎓 | Google IT Automation with Python (Coursera) |
| 🎓 | Cisco CCNA · Cisco Networking Academy — Python Programming |
| 🥇 | HackerRank Gold Badge — Python & Problem Solving |
| 🗣️ | Cambridge English C1 Advanced |

- **29,443+ applicants** applied to Hack with Hyd (Microsoft Hackathon 2024) — I made the cut
- **Finalist**, Hack with Hyd 2025 — held at the Microsoft office, run by Hack2Skill
- Smart India Hackathon (SIH) — pitched a sustainability platform for plastic waste management

---

<div align="center">

**Let's build something.**
📫 amulyaakokkula@gmail.com  ·  📍 Hyderabad, India

</div>



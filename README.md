<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Abhinab%20P%20Kashyap&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=ML%20Engineer%20%7C%20AI%20Builder%20%7C%20B.Tech%20IT%20%40%20KIIT&descAlignY=58&descSize=18&descColor=a78bfa" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=8+production-deployed+ML+%2F+AI+projects;40%25+inference+latency+reduction+%40+NIELIT;89.74%25+accuracy+on+58-class+CV+model;13%2F13+agentic+RAG+eval+pass+rate;Building+at+the+intersection+of+LLMs+%2B+Systems)](https://github.com/abhinab44)

</div>

---

## 🧠 About Me

```python
abhinab = {
    "role"       : "Third-year B.Tech IT @ KIIT University",
    "focus"      : ["ML Engineering", "MLOps", "Agentic AI", "Computer Vision"],
    "internship" : "AI/ML Engineering Intern — NIELIT (Verified)",
    "projects"   : 8,   # production-deployed
    "seeking"    : "ML Engineering / AI Engineering / Data Science Internships",
    "location"   : "Bhubaneswar, India",
}
```

---

## 🏆 Key Metrics

<div align="center">

| 📉 Latency Reduction | 🎯 CV Accuracy | 🤖 RAG Faithfulness | 📐 RMSE Reduction |
|:---:|:---:|:---:|:---:|
| **40%** @ NIELIT | **89.74%** Top-1 (58 classes) | **0.93** avg RAGAS | **14.5%** via stacking |
| 3.05s → 1.83s | 98.23% Top-5 | 13/13 E2E pass rate | XGBoost + LightGBM + Ridge |

</div>

---

## 🚀 Featured Projects

### 🔬 [Physics Study Buddy — Agentic RAG Assistant](https://github.com/abhinab44/Physics_Study_Buddy)
> LangGraph · ChromaDB · Groq llama-3.3-70b · Streamlit · RAGAS

- **8-node LangGraph StateGraph** with self-reflection eval loop enforcing faithfulness ≥ 0.70
- RAG over **32 physics documents** using all-MiniLM-L6-v2 embeddings + LLM-based router (3 routes)
- **13/13 E2E test pass rate** · avg RAGAS faithfulness **0.93** · hardened against 5 adversarial failure modes
- Sliding-window memory (6-message context, per-session UUID)

---

### 🚦 [Indian Traffic Sign Recognition](https://github.com/abhinab44/California-Housing-Production)
> EfficientNetB0 · TFLite · OpenCV · INT8 Quantization

- **89.74% Top-1 / 98.23% Top-5** accuracy on 13,971 images across **58 classes** (10.6× imbalance)
- Model size reduced **72%** (18.8 MB → 5.2 MB) via INT8 quantization + TFLite export
- P95 CPU latency of **6.06 ms** — 8× under the 50 ms ADAS deadline

---

### 🏠 [California Housing — Stacking Ensemble Pipeline](https://github.com/abhinab44/California-Housing-Production)
> XGBoost · LightGBM · scikit-learn · Ridge Meta-Learner

- **14.5% RMSE reduction** (0.4851 → 0.4150) and **18.4% MAE reduction** vs baseline Random Forest
- 12 engineered features: Haversine distances, income ratios, KMeans geo-clusters
- R² = **0.8679** | 95% CI [0.394, 0.435] | 160 RandomizedSearchCV configurations

---

### 📈 [Real-Time Stock Tracker](https://github.com/abhinab44/Realtime-Stock-Tracker) · [Sales Dashboard](https://github.com/abhinab44/Sales-Analytics-Dashboard) · [Live ↗](https://realtime-stock-tracker.onrender.com)
> Plotly Dash · yfinance · Render · gunicorn

- **2 live production apps** on Render — supports any Yahoo Finance ticker (US, NSE, BSE, Crypto, ETF)
- 30s auto-refresh · adaptive SMA overlays · synthetic GBM fallback
- Sales dashboard: 4 reactive charts + 4 KPI cards via a single 5-output callback

---

### 🧪 [Neural Style Transfer System](https://github.com/abhinab44/Neural_Style_Transfer)
> TensorFlow 2.19 · OpenCV · Multithreading · Producer-Consumer Pipeline

- Built during **NIELIT internship** — reduced CPU inference latency by **40%** (3.05s → 1.83s)
- Eliminated UI freeze with `Queue(maxsize=2)` + daemon worker architecture (55× throughput mismatch)
- Zero crashes across 20-min stress tests | P95/P99 latency report authored (end-to-end: 5.4s)

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

**ML / DL**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-009639?style=for-the-badge&logo=xgboost&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

**Agentic AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-6366F1?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4B4B?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**CV / NLP**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge&logoColor=white)

**Backend / Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Data**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=abhinab44&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=ffffff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhinab44&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=ffffff"/>

</div>

---

## 🎓 Education & Certifications

- 🏛️ **B.Tech in Information Technology** — KIIT University, Bhubaneswar *(Expected June 2027)*
- 📜 **AI/ML Engineering Internship** — NIELIT
- 📜 **Data Curation using Python** — NIELIT
- 📜 **AWS Cloud Bootcamp** — NIELIT

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhinab-p-kashyap)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhinab44)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kashyap.abhi4444@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>

</div>

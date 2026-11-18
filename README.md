# 💼 AI Resume & Adzuna Job Matcher

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app-name.streamlit.app)

A zero-friction, intelligent web application built with **Python** and **Streamlit** that parses user resume PDFs using **Gemini AI**, extracts key professional attributes, and fetches verified live job openings using the **Adzuna API**.

---

## 🚀 Features

- **AI-Powered Resume Parsing:** Leverages `gemini-1.5-flash` with low-temperature constraints to rapidly extract key job titles and core skills from uploaded PDF resumes.
- **Live Job Market Integration:** Queries the **Adzuna API** in real time, bypassing fragile scraping proxies to return active listings with direct application links.
- **Advanced Filtering:** Customize search queries by job title, geographic location, and posting timeframe (`max_days_old`).
- **Smart Session State Caching:** Caches parsed resume attributes so adjusting sidebar filters doesn't trigger re-parsing loops.
- **Secure Configuration:** Protects API keys server-side using Streamlit secrets management.

---

## 🛠️ Tech Stack

- **Frontend & App Framework:** [Streamlit](https://streamlit.io/)
- **AI / LLM:** [Google Generative AI SDK](https://ai.google.dev/) (`gemini-1.5-flash`)
- **Job Data Provider:** [Adzuna API](https://developer.adzuna.com/)
- **PDF Extraction:** `pypdf`
- **HTTP Requests:** `requests`

---

## ⚙️ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
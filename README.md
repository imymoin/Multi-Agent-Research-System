# 🔬 ResearchMind — Multi-Agent AI Research System

A multi-agent AI pipeline that autonomously searches, scrapes, writes, and critiques research reports on any topic.

## 🧠 How It Works

Four specialized AI agents collaborate in sequence:

| Step | Agent | Role |
|------|-------|------|
| 01 | **Search Agent** | Finds recent web information via Tavily |
| 02 | **Reader Agent** | Scrapes & extracts deep content from URLs |
| 03 | **Writer Chain** | Drafts a structured research report |
| 04 | **Critic Chain** | Reviews and scores the report |

## 🛠️ Tech Stack

- **LLM:** Mistral AI (mistral-small-latest)
- **Framework:** LangChain (agents + chains)
- **Search:** Tavily API
- **Scraping:** BeautifulSoup4 + Requests
- **UI:** Streamlit
- **Language:** Python 3.13

# 🤖 Blog Writing Agent (BWA)

A stateful, multi-agent AI system built with **LangGraph**, **OpenAI (gpt-4o-mini)**, and **Streamlit** that automates end-to-end blog production—from real-time web research to structured drafting and visual layout planning.

🚀 **[Live Demo](https://my-blog-writing-agent.streamlit.app)**

---

## 🌟 Key Features
- **Research Agent:** Performs live web research using the Tavily API to gather up-to-date sources and context.
- **Outline & Editor Agent:** Structurally plans long-form content with clear section headers and logical flow.
- **Drafting Agent:** Generates comprehensive markdown articles adhering to clear tone and style guidelines.
- **Stateful Workflow Management:** Built on LangGraph state channels to maintain structured data flow across all agents.
- **Streamlit Web Dashboard:** Clean user interface to input blog topics, review live execution, and inspect output markdown.

---

## 🛠️ Tech Stack
- **Frameworks:** LangGraph, LangChain
- **LLM Models & SDKs:** OpenAI (`gpt-4o-mini`), Google GenAI SDK
- **Frontend UI:** Streamlit
- **Tools & Utilities:** Tavily Web Search API, `python-dotenv`

---

## 🚀 Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/123NUTAN/blog-writing-agent.git](https://github.com/123NUTAN/blog-writing-agent.git)
   cd blog-writing-agent
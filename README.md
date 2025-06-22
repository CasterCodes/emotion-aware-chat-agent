# 🧠 Emotion-Aware Chat Agent

A multi-agent conversational AI that classifies user input as either **emotional** or **logical**, and routes the message to an appropriate response agent. Powered by **LangGraph**, **Google Gemini (via LangChain)**, and structured output parsing.

---

## 💡 Features

- 🔀 Message classifier routes input based on emotional vs logical context
- 🤗 Therapist agent provides empathetic, supportive responses
- 📊 Logical agent delivers direct, factual answers
- 🧱 Built using [LangGraph](https://langchain-ai.github.io/langgraph/concepts/why-langgraph/) stateful workflows
- ⚡ Uses `uv` for fast dependency management

---

## 📦 Requirements

- Python 3.11+
- [`uv`](https://github.com/astral-sh/uv) (a faster, drop-in replacement for pip/pip-tools)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/CasterCodes/emotion-aware-chat-agent.git
cd emotion-aware-chat-agent
```
# LangGraph Demo — Exploring Agent Tools with LLMs

This repository contains a **Jupyter Notebook** that demonstrates a beginner-level exploration of the [LangGraph](https://github.com/langchain-ai/langgraph) framework using a simple crypto and world news assistant.

> ⚠️ This is **not** a complete project or production-ready tool — it's just a personal **learning/demo notebook** to understand how LangGraph agents work with real-world tools and LLMs.

---

## 📌 What is LangGraph?

[LangGraph](https://github.com/langchain-ai/langgraph) is a powerful library built on top of LangChain, allowing developers to create **multi-agent workflows** and **stateful, event-driven applications** using large language models. It supports complex control flows like loops, conditionals, and memory using graph-based structures.

---

## 📖 About This Demo

In this notebook, we explore:

- How to use **LangGraph’s prebuilt ReAct agent**
- How to bind **external tools** to a language model (LLM) using LangChain
- How to stream LLM responses step-by-step
- How to integrate **real-world data** using:
  - 🪙 [CoinGecko API](https://www.coingecko.com/en/api) for live Bitcoin prices
  - 🌍 [GNews API](https://gnews.io/) for the latest headlines by country

---

## 🛠️ Technologies Used

- **LangGraph** – for graph-based agent orchestration  
- **LangChain** – for LLM + tool binding  
- **Groq LLaMA 3.1** – fast open-weight LLM via [Groq API](https://console.groq.com)  
- **Jupyter Notebook** – for interactive experimentation  
- **Requests library** – to fetch external data from public APIs  

---

## 🧩 What's Next?

This demo is meant to:

* Understand how LangGraph agents work
* Explore tool use in LLM-powered workflows
* Serve as a starting point for future LangChain/LangGraph projects

You are welcome to expand it by:

* Adding more tools (e.g., weather, stock, Wikipedia)
* Deploying it as a web app
* Exploring multi-step or multi-agent graphs

---

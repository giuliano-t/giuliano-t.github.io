---
layout: default
title: "LLM-Powered Regulatory Auditor for Financial Analysis"
stack: "Python, LLMs, Agentic Workflows, NLP"
priority: "major"
date: 2025-07-04
github: https://github.com/giuliano-t/llm-financial-regulatory-auditor
---

## Automating Financial Risk Analysis for the Bank of England

Financial regulators face the immense challenge of sifting through thousands of pages of unstructured data from corporate earnings calls to identify potential risks. This project demonstrates an **AI-driven multi-agent solution** built around a Bank of England use case.

The system mimics the workflow of a human analyst: a primary AI agent extracts key metrics, and a **supervisor LLM** audits those outputs for relevance and quality, providing a second layer of assurance.

![Agent Architecture Diagram](/assets/images/boe-agent-architecture.png)

---

## My Solution: A Multi-Agent Evaluation Framework

I designed and implemented a structured evaluation pipeline where one LLM supervises another:

1. **Scoring relevance** — each extracted metric is scored against **Prudential Regulation Authority (PRA) 2025 priorities**.  
2. **Justifying the score** — the supervisor provides a written rationale.  
3. **Recommending action** — metrics are flagged to *Keep, Revise, or Remove*, ensuring actionable outputs.  

---

## Key Features

- **Agentic Workflow** — multi-agent architecture where a GPT-4o “meta-agent” supervises Claude.  
- **Context-Aware Prompting** — PRA regulatory context injected directly into prompts.  
- **Automated Data Pipelines** — scripts parse `.csv`, structure into JSON, and batch-process outputs.  
- **Insight Visualization** — aggregated scores highlight patterns, strengths, and weaknesses across metrics.  

---

## Tech Stack

- **Core AI**: OpenAI GPT-4o, Anthropic Claude  
- **Languages & Libraries**: Python, Pandas, NLTK, Gensim  
- **Environment**: Google Colab, Jupyter Notebook  

---

[🔗 View on GitHub](https://github.com/giuliano-t/llm-financial-regulatory-auditor)

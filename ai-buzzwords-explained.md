# 🤖 AI Buzzwords Explained — The Full 2026 Roadmap

![Made with](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)
![Topics](https://img.shields.io/badge/Topics-11-blue)
![Status](https://img.shields.io/badge/Status-Living%20Doc-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> Companion roadmap for the video **"AI Buzzwords Explained (2026)"**.
> If you've ever felt lost hearing terms like *LLM, RAG, MCP, AI Agent* — this is the map that connects all of them.

🎥 **Watch the full video:** [add this video's direct link once published]
📢 **Channel:** https://www.youtube.com/@Trustinly-in
🗺️ **Interactive board (Excalidraw):** https://excalidraw.com/#json=3wWSWqMKHWhTeMxg5ItDe,zMkAIvMgyPw7vDWN0hcbBQ

---

## 📋 Table of Contents

- [1. Foundation](#1-foundation)
- [2. Transformers](#2-transformers)
- [3. Tokens & Output Generation](#3-tokens--output-generation)
- [4. LLMs, Model Types & GenAI](#4-llms-model-types--genai)
- [5. Prompt Engineering](#5-prompt-engineering)
- [6. Context & Memory](#6-context--memory)
- [7. RAG](#7-rag)
- [8. Tools & Function Calling](#8-tools--function-calling)
- [9. MCP](#9-mcp)
- [10. Agents, Multi-Agent & Loop Engineering](#10-agents-multi-agent--loop-engineering)
- [11. Harness & Skills](#11-harness--skills)
- [🎓 Recommended Deep-Dive Videos](#-recommended-deep-dive-videos)

---

## How to use this roadmap

Check off each box as you understand the concept. Every section has a one-line definition, why it matters, and hand-picked videos if you want to go deeper than the main video did.

```
Progress: [ ] 1 → [ ] 2 → [ ] 3 → [ ] 4 → [ ] 5 → [ ] 6 → [ ] 7 → [ ] 8 → [ ] 9 → [ ] 10 → [ ] 11
```

---

## 1. Foundation

### `[ ]` AI
Machines doing tasks that normally need a human brain (understanding, deciding, responding). The umbrella term everything else builds on.

### `[ ]` Machine Learning
Shift from writing rules to training on examples — show the machine enough labeled data and it finds the pattern itself.

### `[ ]` Neural Networks
The structure inside most ML — layers of small units passing signals forward, each layer building on the last, until a final answer comes out.

### `[ ]` Deep Learning
Same neural network idea, just many more layers stacked. Going deep unlocked image recognition, speech, and language models.

**📺 Watch:**
- [By IBM Technology](https://youtube.com/watch?v=qYNweeDHiyU)
- [Difference: AI vs ML vs Deep Learning](https://youtube.com/watch?v=TnPTW1g7Xn0)

[⬆ back to top](#-table-of-contents)

---

## 2. Transformers

The 2017 architecture (from Google's paper *"Attention Is All You Need"*) that reads a whole sentence at once and weighs which words matter most to each other. The reason GPT, Claude, and Gemini exist.

**📺 Watch:**
- [AI Coffee Break with Letitia](https://youtube.com/watch?v=FWFA4DGuzSc)
- [By Code Basics](https://www.youtube.com/watch?v=ZhAz268Hdpw&t=42s)

[⬆ back to top](#-table-of-contents)

---

## 3. Tokens & Output Generation

Models see tokens (chunks turned into numbers), not words. Output is generated one token at a time, predicting the next most likely one.

**📺 Watch:**
- [By Trustinly](https://www.youtube.com/watch?v=8xqnjzCs5pc&t=928s)
- [By Yash Thakkar](https://www.youtube.com/watch?v=S5Uo3qS9wOc&t=34s)

[⬆ back to top](#-table-of-contents)

---

## 4. LLMs, Model Types & GenAI

LLM = a transformer trained on huge amounts of text, fine-tuned to follow instructions.
Models split into **open-weight** (Llama, DeepSeek) vs **closed** (GPT, Claude, Gemini).
LLMs are actually a subset of the bigger category **GenAI** — AI that generates text, images, video, or audio.

**📺 Watch:**
- [By Andrej Karpathy](https://youtube.com/watch?v=7xTGNNLPyMI)
- [By Piyush Garg](https://www.youtube.com/watch?v=K45s2PgywvI&t=3251s)

[⬆ back to top](#-table-of-contents)

---

## 5. Prompt Engineering

Same model, different question, completely different answer. The skill of structuring your ask to get what you actually want — the cheapest, fastest lever anyone can pull to improve AI results.

**📺 Watch:**
- [By Assembly AI](https://youtube.com/watch?v=aOm75o2Z5-o)
- [By Telusko](https://youtu.be/n0VpK1RfYGA)

[⬆ back to top](#-table-of-contents)

---

## 6. Context & Memory

**Context window** = short-term memory, everything the model can currently see. Long conversations push older details out.
**Long-term memory** is a separate system that brings old info back in when needed.

**📺 Watch:**
- [By Network Chuck](https://youtube.com/watch?v=TeQDr4DkLYo)

[⬆ back to top](#-table-of-contents)

---

## 7. RAG
*(Retrieval-Augmented Generation)*

Model retrieves fresh documents first, then answers using that info. Fixes hallucination and outdated knowledge — this is how most support chatbots know your product docs instead of just the internet.

**📺 Watch:**
- [By Apna College](https://youtu.be/Ty8gcCKuwNI)
- [By Krish Naik](https://youtu.be/fZM3oX4xEyg)

[⬆ back to top](#-table-of-contents)

---

## 8. Tools & Function Calling

Model requests an action (search, run code), a system executes it, the result feeds back in. This is the exact moment AI shifted from talking to doing.

> 🛠️ **LangChain** — the most popular framework for wiring this up in code
> 🛠️ **n8n** — the no-code alternative

**📺 Watch:**
- [How tool calling works](https://youtube.com/watch?v=QiRdYCNXAxk)
- [Tool calling by Piyush Garg](https://youtu.be/TlIOk8VuEBU)

[⬆ back to top](#-table-of-contents)

---

## 9. MCP
*(Model Context Protocol)*

An open standard letting AI models plug into any app or data source the same way — think **"USB-C for AI"** instead of custom wiring for every tool.

**📺 Watch:**
- [By Code Basics](https://youtube.com/watch?v=tzrwxLNHtRY)
- [By Abhishek Verramala](https://www.youtube.com/watch?v=t6shxqII3IQ)

[⬆ back to top](#-table-of-contents)

---

## 10. Agents, Multi-Agent & Loop Engineering

An **agent** runs a loop — think, act, observe, repeat — until the goal is done, with minimal human input.
**Multi-agent systems** coordinate several specialized agents through one orchestrator.
Designing that self-running loop is now called **Loop Engineering**.

> 🧩 Common frameworks: **LangGraph**, **CrewAI**

**📺 Watch:**
- [AI Agents explained](https://youtube.com/watch?v=hLJTcVHW8_I)
- [AI agents creation by Chai aur Code](https://youtu.be/B5LZnYYoLtY)

[⬆ back to top](#-table-of-contents)

---

## 11. Harness & Skills

A **harness** is the scaffolding around a raw model — tools, permissions, memory, rules — that turns it into a product like Cursor, Claude Code, or Windsurf.
**Skills** are reusable instructions the harness loads on demand.

```
LLM      = The brain 🧠
Harness  = The operating system around the brain ⚙️
Skills   = Reusable expertise the agent can load 📦
```

To know if all of this is actually working, teams run **LLM Evals** and follow **LLMOps** practices — often with tools like **LangSmith**.

**📺 Watch:**
- [What is an AI agent harness](https://youtube.com/watch?v=e5B2XP7apXs)
- [What is harness engineering](https://youtu.be/IBTeJtMmEac)
- [LLM Evals](https://youtu.be/6W92_t9FveA)
- [All AI concepts in one video — Gaurav Sen](https://youtu.be/OYvlznJ4IZQ)
- [By Chai aur Code](https://www.youtube.com/watch?v=_g2CgoTcVME&t=476s)

[⬆ back to top](#-table-of-contents)

---

## 🎓 Recommended Deep-Dive Videos

If you want to go beyond this roadmap into the full ecosystem in more depth:

- [Recommended video 1 — add link]
- [Recommended video 2 — add link]

---

## 🙌 Support the channel

If this roadmap helped you make sense of AI, consider:
- ⭐ Starring this repo
- 🔔 Subscribing to the channel: https://www.youtube.com/@Trustinly-in
- 💬 Opening an issue/discussion here with which topic you want a full deep-dive video on next

---

<sub>This roadmap is a living document — as tools and terms evolve, this repo will be updated. Contributions and suggested resource links are welcome via PR.</sub>

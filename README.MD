# 🤖 Agentic AI Chatbot Agent – Built in n8n

This project is an *Agentic AI Workflow* built using *n8n.cloud. The AI agent receives a chat message, processes it using a **Google Gemini LLM*, and intelligently uses tools like memory, search (SerpAPI), and a calculator to respond — demonstrating autonomous reasoning and tool use.

---

## 🧠 Project Overview

### 🎯 Purpose
To demonstrate an *agentic AI system* that can:
- Understand input messages
- Use *memory* to retain context across sessions
- Call *external tools* when needed (like SerpAPI or calculator)
- Return useful, accurate, and intelligent responses — automatically

---

## ⚙ Workflow Components

| Node | Description |
|------|-------------|
| 🗨 When chat message received | Entry trigger for the agent |
| 🤖 AI Agent | Core autonomous agent logic |
| 💬 Google Gemini Chat Model | LLM used for understanding and generating responses |
| 🧠 Simple Memory | Stores previous interactions to enable context awareness |
| 🔍 SerpAPI | External web search for real-time data |
| 🧮 Calculator | Performs math operations when requested |

---

## 🚀 How to Use

1. Open this workflow in your *n8n.cloud* or *self-hosted* instance
2. Set up the following credentials:
   - *Google Gemini API*
   - *SerpAPI key*
3. Import the exported workflow file: chatbot-agentic-workflow.json
4. Activate the workflow
5. Send a chat message (e.g., “What’s the weather in Bangalore?” or “Calculate 234 + 789”)

The agent will:
- Think about the request
- Use tools if needed
- Respond based on real-world data or memory

---

## 📁 Files

- chatbot-agentic-workflow.json – The n8n exported file of this agentic workflow

---

## 📸 Screenshot

![Workflow Screenshot](https://github.com/sharan-88/smart-query-handler/blob/main/Screenshot%202025-07-24%20123245.png)  


---

## 📄 Tech Stack

- [n8n](https://n8n.io) – Low-code workflow automation
- [Google Gemini](https://deepmind.google/technologies/gemini/)
- [SerpAPI](https://serpapi.com)
- Built-in Memory + Tool use

---

## 🎓 Skills Demonstrated

- Agentic reasoning
- Tool selection and invocation
- Memory integration
- Chat-based interface automation
- Practical use of LLMs in workflows

---

## 📄 License

MIT License – feel free to use, modify, and build upon this project.

---

## 🤝 Acknowledgments

Built for college placement assignment on *Agentic AI*  
Created using n8n.cloud with LLM + tool integrations.

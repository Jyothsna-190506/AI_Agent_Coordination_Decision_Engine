🤖 AI Agent Coordination & Decision Engine

Infosys Springboard Virtual Internship 7.0 — Multi-Agent Coding Assistant System
Built with LangChain + Google Gemini 1.5 Flash

📌 Project Overview

A multi-agent AI system where specialized agents collaborate to assist developers with coding tasks. Each agent has a defined role, and a central Decision Engine (Orchestrator) coordinates them based on the user's request.

User Input
   
    ↓

Decision Engine (Orchestrator)
   
    ↓

┌──────────────────────────────────────────────┐
│  Code Generator → Code Reviewer → Test Writer → Doc Agent  │
└──────────────────────────────────────────────┘
   
    ↓

Final Output (code + review + tests + docs)

📁 Project Structure

ai-agent-coordination-engine/

│

├── agents/

│   └── code_generator_agent.py   ← Agent 1: Code Generator (LangChain + Gemini)

│

├── main.py                        ← CLI entry point (interactive session)

├── requirements.txt               ← Python dependencies

├── .env                           ← API key (NOT pushed to GitHub)

├── .gitignore                     ← Protects .env from being committed

└── README.md                      ← This file

👤 Author

Jyothsna Priya Sunkara

Infosys Springboard Virtual Internship 7.0

Multi-Agent AI System | Python Full-Stack Track

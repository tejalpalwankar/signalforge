# SignalForge  
### Multi-Agent Launch Intelligence Engine

SignalForge is a coordinated AI system that converts fragmented public web data into structured, executive-ready product launch intelligence.

Built with Streamlit, GPT-4o, and Firecrawl, the system deploys specialized agents that independently analyze positioning, sentiment, and performance — then synthesize findings into actionable strategy outputs.

---

## Why SignalForge?

Product and GTM teams often face three problems:

1. Competitive insights are scattered across press releases, blogs, and landing pages  
2. Market sentiment lives in noisy forums and review platforms  
3. Launch performance metrics are distributed across media mentions and partial data  

SignalForge orchestrates multiple expert AI agents to transform those signals into a unified intelligence brief.

---

## Architecture Overview

SignalForge uses a coordinated multi-agent framework:

| Agent | Role | Output Type |
|-------|------|------------|
| Launch Strategy Analyst | Evaluates positioning, differentiation, pricing signals, messaging | Strategic review |
| Market Perception Analyst | Extracts sentiment drivers from social + reviews | Sentiment brief |
| Performance Metrics Analyst | Tracks adoption, traction, KPIs, press coverage | KPI snapshot |

Each agent:
- Uses live web search + crawl tools
- Produces evidence-backed outputs
- Appends a source reference section

A coordinating team layer routes requests and ensures structured formatting consistency.

---

## Core Capabilities

### 1. Competitive Launch Review
- Positioning breakdown
- Strengths vs weaknesses table
- Tactical learnings
- Strategic implications

### 2. Market Sentiment Snapshot
- Positive drivers
- Negative drivers
- Narrative trend summary

### 3. Launch Performance Dashboard
- Adoption metrics (if available)
- Engagement signals
- Press volume indicators
- Qualitative traction markers

All outputs are auto-formatted in Markdown for executive readability.

---

## Technology Stack

| Layer | Tooling |
|-------|---------|
| Interface | Streamlit |
| LLM | OpenAI GPT-4o |
| Web Data | Firecrawl (async search + crawl) |
| Agent Framework | Agno multi-agent orchestration |
| Runtime | Python |

---

## System Design

SignalForge uses:

- Modular agent definitions
- Coordinated routing logic
- Structured formatting prompts
- Retry + exponential backoff handling
- Secure key injection via environment variables or UI

This design enables:
- Extensibility (add new analysts easily)
- Agent specialization
- Deterministic formatting structure
- Source transparency

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/signalforge.git
cd signalforge

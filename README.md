# Awesome AI Agents 2026 🤖

> **The complete guide to AI agent frameworks, tools, and platforms.** What's actually worth using in 2026.

AI agents went from research demos to production tools. This list separates the real from the hype.

⭐ **Star this repo** — updated monthly with new tools and benchmarks.

---

## Agent Frameworks

### Production-Ready

| Framework | Language | Stars | Best For |
|-----------|----------|-------|----------|
| **Claude Code** | Python/TS | — | Coding, file editing, terminal |
| **OpenAI Agents SDK** | Python | 15K+ | General-purpose agents |
| **LangGraph** | Python | 8K+ | Complex multi-step workflows |
| **CrewAI** | Python | 20K+ | Multi-agent collaboration |
| **AutoGen** | Python | 35K+ | Research, multi-agent debate |
| **Semantic Kernel** | C#/Python | 22K+ | Enterprise, Microsoft stack |

### Emerging

| Framework | Language | Stars | Best For |
|-----------|----------|-------|----------|
| **Mastra** | TypeScript | 5K+ | TS-first agents |
| **Pydantic AI** | Python | 3K+ | Type-safe agents |
| **Smolagents** | Python | 2K+ | Minimal, HuggingFace |
| **Agency Swarm** | Python | 3K+ | Custom agent swarms |

### Build From Scratch (No Framework)

| Approach | Lines | Dependencies | Tutorial |
|----------|-------|-------------|----------|
| Raw Claude API | 50 | 1 (anthropic) | [AI Agent Starter Kit](https://github.com/spinov001-art/ai-agent-starter-kit) |
| Raw OpenAI API | 60 | 1 (openai) | OpenAI docs |
| Raw Ollama | 40 | 1 (ollama) | Ollama docs |

**My recommendation:** Start with raw API calls. Add a framework only when you need multi-agent coordination or complex state management.

## Tool Calling & MCP

| Tool | What It Does | Link |
|------|-------------|------|
| **MCP (Model Context Protocol)** | Standard for AI ↔ tool communication | modelcontextprotocol.io |
| **Claude Desktop** | Desktop app with MCP support | claude.ai |
| **Apify MCP Actors** | 859+ MCP-compatible scrapers | apify.com/store |
| **Composio** | 150+ tool integrations for agents | composio.dev |
| **Toolhouse** | Managed tool infrastructure | toolhouse.ai |

**MCP Cookbook:** [15 ready-to-use MCP servers](https://github.com/spinov001-art/claude-mcp-cookbook)

## Coding Agents

| Agent | Price | Best For |
|-------|-------|----------|
| **Claude Code** | Usage-based | Terminal, file editing, git |
| **Cursor** | $20/mo | IDE-integrated coding |
| **Windsurf** | $15/mo | Fast completions |
| **Aider** | Free (OSS) | Terminal, git-aware |
| **Continue** | Free (OSS) | VS Code/JetBrains |
| **Cline** | Free (OSS) | VS Code, autonomous |

## Autonomous Agents

| Agent | What It Does | Status |
|-------|-------------|--------|
| **Devin** | Autonomous SWE | Production (waitlist) |
| **OpenHands** | Open-source Devin | Production |
| **SWE-Agent** | Bug fixing | Research |
| **AutoGPT** | General autonomy | Experimental |
| **BabyAGI** | Task decomposition | Archived |

## Agent Infrastructure

| Tool | Purpose |
|------|---------|
| **LangSmith** | Agent observability, tracing |
| **Braintrust** | Eval + monitoring |
| **Humanloop** | Prompt management |
| **Helicone** | LLM proxy, caching, logging |
| **Portkey** | AI gateway, reliability |

## Key Concepts

```
Agent = LLM + Tools + Loop

1. User gives task
2. LLM decides which tool to use
3. Tool executes and returns result
4. LLM decides next step (or finish)
5. Repeat until done
```

## Learning Path

1. **Start here:** [AI Agent Starter Kit](https://github.com/spinov001-art/ai-agent-starter-kit) — 50-line agent
2. **Add tools:** [Claude MCP Cookbook](https://github.com/spinov001-art/claude-mcp-cookbook) — 15 MCP examples
3. **Scale up:** Pick a framework (CrewAI for multi-agent, LangGraph for workflows)

## Related

- [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 77+ scraping tools for agent data
- [LLM Data Extraction](https://github.com/spinov001-art/llm-data-extraction) — AI-powered scraping
- [Free Developer Tools 2026](https://github.com/spinov001-art/free-developer-tools-2026) — 200+ free tools

## Need Custom AI Agents?

I build production AI agents for companies — data collection, research, automation. **[Hire me →](https://spinov001-art.github.io)**

---

**Know a tool I missed?** [Open an issue](https://github.com/spinov001-art/awesome-ai-agents-2026/issues).

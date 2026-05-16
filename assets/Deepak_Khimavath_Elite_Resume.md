# Deepak Khimavath

**AI Platform Engineer | Developer Tools | Agentic Systems**  
Bengaluru, India | +91 7204209095 | deepakkhimavath@gmail.com  
LinkedIn: https://linkedin.com/in/deepak-khimavath-338074219 | GitHub: https://github.com/DeepakkhimavathBB

## Summary

AI platform and developer tools engineer building production AI systems, internal developer tooling, and event-driven financial infrastructure. Built a production Azure DevOps PR review agent, a Visual Studio AI development companion used by 20+ engineering/product users, and an active R&D 6-agent code intelligence pipeline. Owns 3 production financial microservices in a 50+ service EDA platform; delivered a 98% latency reduction by modernizing SP-driven processing toward event-driven service flows.

## Core Skills

**AI / Agents:** LLM infrastructure, agentic workflows, multi-agent orchestration, RAG, Qdrant, LlamaIndex, LangFuse, prompt evaluation, tool calling, code intelligence  
**Backend / Platform:** C#/.NET, Python, FastAPI, Azure Functions, Azure DevOps REST API, microservices, EDA, message queues, idempotency, retry-safe workflows  
**Data / Infra:** MS SQL Server, Dapper DAL, Azure Event Grid, App Service, Storage, Monitor/Logs, CI/CD, OAuth/JWT, MSAL.NET, WebView2  
**Frontend / Tooling:** Visual Studio SDK, VSIX, WPF, VSCT, JavaScript, React, Node.js, Flask, Docker, GitHub Actions

## Experience

### Eton Solutions — Trainee Engineer
**Jul 2025 - Present | Wealth management / FinTech platform**

- Own 3 production financial microservices end-to-end: **EliminationService**, **DFRulesProcessorService**, and **JournalEntryPersistService**, covering trade elimination, rules evaluation, and ledger persistence workflows.
- Reduced a critical event-driven processing bottleneck from **15-20 hours to under 15 minutes** across a 50+ service distributed architecture by modernizing SP-driven financial processing into queue-backed service flows.
- Built transaction-processing workflows spanning bank feed ingestion, validation, enrichment, journal entry creation, and MS SQL persistence using Dapper DAL, structured logging, and traceable service execution.
- Strengthened reliability across distributed services with idempotency, retry-safe processing, structured error handling, OAuth/JWT auth patterns, Azure Monitor/Logs, and Azure DevOps CI/CD release discipline.
- Built production AI developer tooling: an autonomous PR review agent and **Eton Dev**, a Visual Studio AI companion used by **20+ engineering/product users** for review, debugging, PR, and AI-assisted workflows.
- Recognized by Director of Engineering and Chief Solution Architect for LLM, agentic AI, developer tooling, and platform contributions.

### Spurzee Technologies — Full-Stack Developer Intern
**Jul 2024 - Jun 2025 | Trading systems / FinTech**

- Built a real-time stock analytics platform with live candlestick visualization, market data APIs, technical indicators, and automated pattern detection for 15-20 trading patterns.
- Integrated LLM-assisted trade signal generation and automated options workflows, improving data-processing throughput by **25%**.
- Trained and deployed a Random Forest stock-price prediction model; managed model development through cloud deployment on AWS/DigitalOcean.

## Selected Engineering Work

### PR Review Agent — Production Azure DevOps Code Review Platform
- Built serverless Azure Functions architecture: HTTP webhook acknowledgement in **<1s**, queue-triggered LLM processor for long-running review work, and automated PR comments/votes.
- Reviewed **150+ PRs org-wide in 20-30 days** with Jira context, diff analysis, prior-finding extraction, context-aware delta reviews, and LangFuse tracing.
- Implemented @agent commands (`re-review`, `skip`, `focus`, `context`, `explain`, `help`) with nested Azure DevOps thread replies and REST fallback for thread ID resolution.
- Added event normalization, commit-keyed deduplication, confidence-based finding downgrade, and multi-repo runtime routing from PR URLs.

### Eton Dev — Production AI Development Companion
- Built Visual Studio VSIX/WebView2 tool with AI chat, pre-PR code review, bug investigation, auto-fix, commit flow, and Azure DevOps PR lifecycle in one panel.
- Designed multi-provider LLM routing across Claude, Mistral, GPT/Azure OpenAI, and custom backends with repo-aware routing and retry handling.
- Implemented two-phase auto-fix: planner validates safe edit scope; patch generator applies anchored old/new block replacements with atomic writes and backups.
- Built enterprise auth flows with MSAL WAM broker, browser SSO fallback, JWT caching, and Azure DevOps IdentityPicker/TFS storage-key GUID reviewer resolution.

### Eton ARC — Active R&D Multi-Agent Code Intelligence Pipeline
- Designed 6-agent Jira-to-code pipeline: Triage -> grep-first Discovery -> parallel Specialist Council -> Moderator -> Opus principal review -> Execute.
- Built dual-layer retrieval with Qdrant/LlamaIndex: source code chunks plus structured service profiles across 11 services, using exact identifier search before semantic retrieval.
- Produces code-grounded execution plans with file-level diffs, PR description, build order, xUnit test stubs, AC coverage, regression risks, and GO / CONDITIONAL-GO / NO-GO gates.

### Academic Research — Quantum Computing for Insurance Risk
- Co-authored IJIRT paper: **Insurance Risk Prediction Using Quantum Computing and Machine Learning** (Jan 2025), exploring hybrid quantum-classical risk prediction using QSVM/quantum concepts, ML baselines, Flask workflows, and risk dashboards.

## Education

**B.E. Computer Science & Engineering**, PES Institute of Technology and Management, Shivamogga  
2021 - 2025 | GPA: 8.62 / 10

## Recognition

- Recognized by Director of Engineering and Chief Solution Architect for AI platform/tooling contributions.
- IEEE/IJIRT research publication on quantum computing and insurance risk prediction.
- Alumni mentor for agentic AI, RAG, developer tooling, and production AI engineering.

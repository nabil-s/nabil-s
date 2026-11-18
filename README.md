### Hi, I'm nabil-s 👋

**Building toward AI Architect: one small, production-quality AI app every month,
each with an architecture diagram, ADRs, evals, and measured cost per request.**

## Monthly AI builds

| # | Month | App | Architecture concept | Status |
|---|---|---|---|---|
| 1 | Dec 2026 | invoice-extract | Structured extraction with schema validation and field-level evals | 🔲 planned |
| 2 | Jan 2027 | docs-rag-evals | RAG with retrieval and faithfulness evals | 🔲 planned |
| 3 | Feb 2027 | ops-agent | Tool-using agent with loop limits and failure handling | 🔲 planned |
| 4 | Mar 2027 | mcp-notes | MCP server and client | 🔲 planned |
| 5 | Apr 2027 | model-router | Multi-model routing with a per-request cost ledger | 🔲 planned |
| 6 | May 2027 | guardrail-proxy | Guardrails: PII redaction, prompt-injection red-team evals | 🔲 planned |
| 7 | Jun 2027 | llm-trace-dash | Observability: tracing, latency and cost dashboard | 🔲 planned |
| 8 | Jul 2027 | embed-finetune | Embedding fine-tuning measured against a RAG baseline | 🔲 planned |
| 9 | Aug 2027 | semantic-cache | Semantic and prompt caching for cost and latency | 🔲 planned |
| 10 | Sep 2027 | judge-calibrate | LLM-as-judge calibration against human labels | 🔲 planned |
| 11 | Oct 2027 | batch-pipeline | Async batch processing with idempotent, resumable jobs | 🔲 planned |
| 12 | Nov 2027 | prompt-ci | Versioned prompts with eval gates in CI | 🔲 planned |

Every app follows the same standard: problem statement, Mermaid architecture diagram,
ADRs, eval results, cost per request, limitations, and CI running lint, tests and evals.
Apps run free by default on a local model, with Claude as an opt-in paid backend.

## Skills

- **Focus (built in public above):** LLM application architecture, RAG, agents and tool use,
  MCP, evals, cost and latency engineering, guardrails, observability
- **Languages:** Python (primary for the builds above); earlier work in Java and Go
- **Delivery:** CI/CD (GitHub Actions; earlier Jenkins pipelines), Docker, SonarQube, AWS (S3, CodeBuild)

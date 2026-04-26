# Production LLMOps

Gateways, observability, caching strategies and cost / SLO discipline &mdash; the operational layer that turns a working prototype into a service you can run at scale.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_LLMOps/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | LLM Gateways | in development | What a gateway does; LiteLLM OpenAI-compat shim; Portkey; OpenRouter; custom patterns; multi-provider failover; PII scrubbing; deployment shapes (sidecar, central, edge). |
| 02 | Observability | in development | Trace structure for agents (request, completion, tools, sub-spans); OpenTelemetry GenAI semantic conventions; Langfuse, Phoenix, Helicone, LangSmith; sampling; PII handling. |
| 03 | Caching &amp; Routing | in development | Three cache layers (exact, semantic, prompt); Anthropic prompt caching (TTL, breakpoints, write cost); OpenAI implicit cache; GPTCache dangers; routing patterns; A/B and shadow traffic. |
| 04 | Cost &amp; SLOs | in development | Token economics (input/output/cached/batched); TTFT/TPS/p95; cost-per-task metric; capacity planning; rate limiting; SLO design; budget enforcement; usage forecasting. |

> <strong>Status:</strong> sub-hub created with roadmap. Leaf decks land progressively over upcoming sessions.

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.

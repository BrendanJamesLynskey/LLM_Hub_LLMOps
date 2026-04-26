# Production LLMOps

Gateways, observability, caching strategies and cost / SLO discipline &mdash; the operational layer that turns a working prototype into a service you can run at scale.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_LLMOps/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [LLM Gateways](https://brendanjameslynskey.github.io/LLMOps_01_Gateways/) | live | What a gateway does; LiteLLM OpenAI-compat shim; Portkey; OpenRouter; custom patterns; multi-provider failover; PII scrubbing; deployment shapes (sidecar, central, edge). |
| 02 | [Observability](https://brendanjameslynskey.github.io/LLMOps_02_Observability/) | live | Trace structure for agents (request, completion, tools, sub-spans); OpenTelemetry GenAI semantic conventions; Langfuse, Phoenix, Helicone, LangSmith; sampling; PII handling. |
| 03 | [Caching &amp; Routing](https://brendanjameslynskey.github.io/LLMOps_03_Caching_and_Routing/) | live | Three cache layers (exact, semantic, prompt); Anthropic prompt caching (TTL, breakpoints, write cost); OpenAI implicit cache; GPTCache dangers; routing patterns; A/B and shadow traffic. |
| 04 | [Cost &amp; SLOs](https://brendanjameslynskey.github.io/LLMOps_04_Cost_and_SLOs/) | live | Token economics (input/output/cached/batched); TTFT/TPS/p95; cost-per-task metric; capacity planning; rate limiting; SLO design; budget enforcement; usage forecasting. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.

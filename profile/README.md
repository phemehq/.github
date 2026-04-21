### Pheme is an **intelligence layer for Prometheus and Grafana stacks**. It sits alongside your existing observability tooling, watching the same metric streams, but surfacing anomalies before threshold-based alerts fire.

## What it does

| Capability | Description |
|---|---|
| **Anomaly Detection** | Passively watches Prometheus remote_write streams and flags deviations before alert rules trigger |
| **Signal Enrichment** | Publishes annotated alerts back to Alertmanager and Grafana without replacing them |
| **Incident Summarizer** | Generates AI-written incident summaries for operators when anomalies cluster |
| **Runbook RAG** | Retrieves relevant runbook sections and past incident context at alert time |
| **Pluggable LLM Backend** | Bring your own model — OpenAI, Anthropic, or local inference |

## What it is not

Pheme is purely additive. Remove it and your existing stack is unchanged.

- Not a monitoring system — Prometheus remains that
- Not a metrics database — Prometheus and Thanos remain that
- Not a Grafana replacement — Grafana remains that
- Not a replacement for alert rules — those keep working alongside it

Inspired by the mythological Pheme — the first to know, the one who never slept.

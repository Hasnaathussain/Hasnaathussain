```text
$ whoami
Hasnaat Hussain — AI Systems Architect & Agentic Engineer

$ systemctl status agentic-orchestrator.service
● agentic-orchestrator.service - AI Systems & Orchestration Layer
     Loaded: loaded (/etc/systemd/system/agentic-orchestrator.service; enabled)
     Active: active (running) since Tue 2026-07-07 18:35:40 UTC
     Detail: Specializing in Multi-Agent Memory, LLM Routing, and High-Performance Backends
     Status: 22 OSS contributions across 15 flagship repositories (~400k★ combined)
```

---

## 🧬 Engineering Focus

I engineer intelligent systems at the intersection of **Generative AI**, **multi-agent coordination**, and **core system runtimes**. My focus is on resolving race conditions in agentic memory models, throughput and latency bottlenecks in LLM routing layers, and type-safety/validation in SDKs.

---

## 🚀 Featured Contributions

### 🧠 Generative AI & Orchestration
* **[pydantic-ai #6098](https://github.com/pydantic/pydantic-ai/pull/6098) (Merged)**: Resolved AWS Bedrock Converse validation issues when user turns carry media attachments immediately following tool results.
* **[crewAI #6377](https://github.com/crewAIInc/crewAI/pull/6377)**: Implemented automatic tool return serialization for dictionary/list outputs to clean JSON strings, preventing LLM parser failure.
* **[litellm #31070](https://github.com/BerriAI/litellm/pull/31070)**: Added dynamic parameter pruning (`drop_params`) for Anthropic pass-through endpoint to prevent HTTP 400 validation failures.
* **[litellm #31081](https://github.com/BerriAI/litellm/pull/31081)**: Gated proxy user budget checks on model discovery routes to prevent initialization failures.
* **[graphiti #1604](https://github.com/getzep/graphiti/pull/1604)**: Bound `LLMConfig.max_tokens` constraints to OpenAI-compatible clients to prevent context-window exhaustion.

### 🌐 Web, Tooling & Infrastructure
* **[jinja2 #2212](https://github.com/pallets/jinja/pull/2212)**: Intercepted invalid dictionary template names inside loader entry points to raise early, explicit TypeErrors, avoiding unhashable cache key crashes under Python 3.14.
* **[flask #6083](https://github.com/pallets/flask/pull/6083)**: Restored test collection compatibility under Pytest 9.1+ by fallback importing the renamed `NOTSET` monkeypatch sentinel.
* **[werkzeug #3204](https://github.com/pallets/werkzeug/pull/3204)**: Fixed credentials data-loss in `uri_to_iri`/`iri_to_uri` mapping logic.
* **[click #3668](https://github.com/pallets/click/pull/3668)**: Resolved progress undercounting in ProgressBar finish when a custom update step is configured.
* **[keras #23222](https://github.com/keras-team/keras/pull/23222)**: Standardized mapping validation of target labels in training data adapters.
* **[sqlglot #7807](https://github.com/tobymao/sqlglot/pull/7807) (Merged)**: Restructured parentheses tuple parsing priorities to retain multiple items inside nested SQLite tuples containing subqueries.
* **[BentoML #5643](https://github.com/bentoml/BentoML/pull/5643)**: Gated generic argument length indexing on bare iterators/generators to prevent server compilation crashes.

---

## 📈 Activity Grid

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hasnaathussain/Hasnaathussain/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Hasnaathussain/Hasnaathussain/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Grid Snake" src="https://raw.githubusercontent.com/Hasnaathussain/Hasnaathussain/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</p>

---

## 💬 Let's Connect

```bash
$ ssh Hasnaathussain@github.com
- Location: Islamabad, Pakistan
- Email   : hasnaat.hussain.2@gmail.com
- LinkedIn: linkedin.com/in/hasnaathussain
```

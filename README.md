<div align="center">
<img src="./assets/neofetch.svg" alt="Hasnaat Hussain — Terminal Card" width="100%"/>
<p><strong>AI infrastructure · data systems · developer tooling</strong></p>
<p><a href="https://hasnaat-portfolio-gilt.vercel.app/">Portfolio</a> · <a href="https://github.com/Hasnaathussain?tab=repositories">Repositories</a></p>
</div>

I build and debug AI infrastructure: inference, serving, LLM tooling, data systems, and observability. Six focused fixes have merged upstream; twelve more are in maintainer review or repository-controlled CI gates. Each contribution is tied to a concrete failure mode and backed by tests.

### Selected systems

- [nn_inference](https://github.com/Hasnaathussain/nn_inference) — C++17 ONNX CPU runtime with SIMD GEMM dispatch and activation memory planning.
- [OmniChat Showcase](https://github.com/Hasnaathussain/OmniChat-Showcase) — sanitized case study for a CPU-first multimodal RAG assistant; the operational runtime remains private.
- [Portfolio site](https://hasnaat-portfolio-gilt.vercel.app/) — live project and upstream-contribution index, refreshed from public GitHub metadata.

### Contribution landscape

<div align="center">

![3D Contribution Graph](./profile-3d-contrib/profile-night-green.svg)

</div>

### Open source contributions

#### Merged highlights

| Project | PR | Impact |
|:--------|:---|:-------|
| **ultralytics/ultralytics** | [#25153](https://github.com/ultralytics/ultralytics/pull/25153) | RT-DETR decoder `max_det` redesign |
| **plotly/plotly.js** | [#7768](https://github.com/plotly/plotly.js/pull/7768) | Tick-format exponent precision fix |
| **pydantic/pydantic-ai** | [#6098](https://github.com/pydantic/pydantic-ai/pull/6098) | Bedrock tool-result attachment fix |
| **tobymao/sqlglot** | [#7807](https://github.com/tobymao/sqlglot/pull/7807) | Nested SQLite tuple parsing |
| **mlflow/mlflow** | [#25807](https://github.com/mlflow/mlflow/pull/25807) | Shared-provider Strands foreign-span guard |
| **apache/datafusion** | [#24484](https://github.com/apache/datafusion/pull/24484) | Custom physical-expression inputs in CASE evaluation |

<details>
<summary><strong>Current upstream work · 12 open PRs</strong></summary>
<br/>

| Project | PR | State | Impact |
|:--------|:---|:------|:-------|
| **vllm-project/vllm** | [#49639](https://github.com/vllm-project/vllm/pull/49639) | Open · review required | RMSNorm precision boundary for speculative decoding |
| **bentoml/BentoML** | [#5671](https://github.com/bentoml/BentoML/pull/5671) | Open · review required | Sync timeout capacity-limiter lifetime |
| **BerriAI/litellm** | [#32452](https://github.com/BerriAI/litellm/pull/32452) | Open · review required | Embedding dimensions `drop_params` handling |
| **pandas-dev/pandas** | [#66209](https://github.com/pandas-dev/pandas/pull/66209) | Open · changes requested | Business-day resampling edge alignment; requested examples answered |
| **BerriAI/litellm** | [#31070](https://github.com/BerriAI/litellm/pull/31070) | Open · review required | Anthropic pass-through parameter filtering |
| **getzep/graphiti** | [#1604](https://github.com/getzep/graphiti/pull/1604) | Open · maintainer-approved; behind/workflow gate | OpenAI generic-client `max_tokens` config |
| **Arize-ai/phoenix** | [#15584](https://github.com/Arize-ai/phoenix/pull/15584) | Open · review required | Cursor-paginated large span dataframe exports |
| **dstackai/dstack** | [#4293](https://github.com/dstackai/dstack/pull/4293) | Open · review required | Capacity-release wake-up for pending retry runs |
| **OpenHands/OpenHands** | [#17570](https://github.com/OpenHands/OpenHands/pull/17570) | Open · review required; human note pending | Monaco diff-model teardown lifecycle |
| **OpenHands/OpenHands** | [#17573](https://github.com/OpenHands/OpenHands/pull/17573) | Open · review required; human note pending | Restore terminal history from persisted conversation events |
| **OpenHands/OpenHands** | [#17575](https://github.com/OpenHands/OpenHands/pull/17575) | Open · review required; human note pending | Mobile automation edit-dialog viewport and scrolling |
| **1mcp-app/agent** | [#557](https://github.com/1mcp-app/agent/pull/557) | Open · CodeRabbit pass; maintainer review pending | MCP 2026 era-aware conformance verdicts |

<sub>Live upstream state refreshed 2026-09-21 · 6 merged · 12 open upstream PRs</sub>

</details>

<sub>Focused fixes in AI and data infrastructure. Public work is listed above; generated activity assets remain available in the repository.</sub>

# PYXIS3

**Autonomous AI that runs your cloud and data-center infrastructure operations.**

[pyxis3.ai](https://pyxis3.ai) — PYXIS3 is the autonomous operator that connects to your accounts across AWS, Google Cloud, Azure, VMware, Nutanix, and on-prem, and runs the estate end to end, within your guardrails, across five dimensions: **cost, capacity, reliability, security, and governance**.

This organisation is our open-source home: the infrastructure and AI-infrastructure tooling we build in the open.

## What PYXIS3 does

PYXIS3 is an operator, not a dashboard. It connects to your accounts, models every resource, and runs a continuous loop — understand, decide, act, verify — grounded in the FinOps Framework and the AWS Well-Architected pillars. It retires idle and orphaned resources, schedules non-production off-hours, rightsizes from live utilisation, sizes and maintains commitments, reinforces workloads running hot, hardens exposures, and enforces policy — executing the reversible changes itself within your guardrails (lever allow-list, per-action and per-run caps, change-freeze windows, a pre-change baseline re-check, and one-click rollback) and holding the higher-impact ones, such as multi-year commitments, for your approval.

One predictable subscription, priced on the infrastructure it manages, the way cloud platforms charge — never a share of savings. The savings it produces are shown as return on that subscription.

## Open source

The infrastructure and AI-infrastructure tooling we build in the open.

| Repository | Purpose |
|---|---|
| [`lens`](https://github.com/pyxis3-ai/lens) | In-cluster Kubernetes observability with LLM-endpoint discovery (vLLM, TGI, llama.cpp, Ollama) and in-browser `kubectl exec`. Live at [`lens.pyxis3.ai`](https://lens.pyxis3.ai). |
| [`vllm-bench`](https://github.com/pyxis3-ai/vllm-bench) | TTFT and TPOT benchmarking for OpenAI-compatible inference endpoints across vLLM, TGI, llama.cpp, and Ollama. |
| [`llm-serving-cookbook`](https://github.com/pyxis3-ai/llm-serving-cookbook) | Production recipes for Kubernetes-native model serving: vLLM on EKS, KEDA autoscaling, token economics, runtime selection. |
| [`noor`](https://github.com/pyxis3-ai/noor) | Multilingual AI semantic search over the Qur'an and classical Arabic literature. Sentence-Transformers and sqlite-vec. Live at [`noor.pyxis3.ai`](https://noor.pyxis3.ai). |
| [`awesome-model-agnostic-llm`](https://github.com/pyxis3-ai/awesome-model-agnostic-llm) | Curated index of open-source LLM-serving tooling: serving runtimes, routers, evaluators, and standards. |

## Contact

- Website: [pyxis3.ai](https://pyxis3.ai)
- Email: [ops@pyxis3.ai](mailto:ops@pyxis3.ai)
- LinkedIn: [/company/pyxis3](https://www.linkedin.com/company/pyxis3)
- Founder: [Omar Abdrabo (@oabdrabo)](https://github.com/oabdrabo)

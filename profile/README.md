# PYXIS3

**Model-agnostic LLM serving infrastructure** — the Kubernetes-native control plane that lets enterprises run open-weight language models in production without locking into a single cloud, model vendor, or inference runtime.

The category did not exist as a named sub-segment of AI infrastructure five years ago. Today it is one of the most strategically contested layers of the enterprise AI stack, and the UK does not yet have a domestic leader in it.

## Why we exist

Production LLM deployment in 2026 faces three independent forms of lock-in:

1. **Cloud lock-in** — your inference fleet lives on one cloud's GPUs (AWS, GCP, Azure); moving a model means re-implementing the serving stack
2. **Model-vendor lock-in** — your control plane is bound to one MLOps platform; moving means losing audit, lineage, and fair-share scheduling
3. **Runtime lock-in** — your model is wired to one inference runtime (vLLM, TGI, Triton, SGLang); moving means re-tuning latency and throughput from scratch

Each lock-in is independent. Each has a different cost to break. None of the existing platforms solves all three. **PYXIS3 is the operations layer that lets you mix and match** — the same control plane drives the same models on the same KPIs across heterogeneous fleets: cloud, on-prem, mixed.

## Public repositories

| Repository | Purpose | License |
|---|---|---|
| [`pyxis-arch`](https://github.com/pyxis3-ai/pyxis-arch) | Architecture thesis — Funnel-Engine-Lens model, runtime-adapter abstraction, fair-share GPU scheduling, audit/lineage across runtime migration | MIT |
| [`vllm-bench`](https://github.com/pyxis3-ai/vllm-bench) | TTFT + TPOT benchmarking for OpenAI-compatible inference endpoints — vLLM, TGI, llama.cpp, Ollama | MIT |
| [`llm-serving-cookbook`](https://github.com/pyxis3-ai/llm-serving-cookbook) | Production recipes for Kubernetes-native vLLM serving — vLLM-on-EKS, KEDA autoscaling, token economics, TTFT optimisation, runtime selection | Apache-2.0 |
| [`lens`](https://github.com/pyxis3-ai/lens) | In-cluster Kubernetes observability with LLM-endpoint discovery for vLLM / TGI / llama.cpp / Ollama. In-browser `kubectl exec`. Live at [`lens.pyxis3.ai`](https://lens.pyxis3.ai) | MIT |
| [`noor`](https://github.com/pyxis3-ai/noor) | Multilingual AI semantic search over Qur'an + classical Arabic literature. Sentence-Transformers + sqlite-vec. Live at [`noor.pyxis3.ai`](https://noor.pyxis3.ai) | MIT |
| [`awesome-model-agnostic-llm`](https://github.com/pyxis3-ai/awesome-model-agnostic-llm) | Curated index of model-agnostic LLM tooling — serving runtimes, routers, evaluators, standards | CC0-1.0 |

## Contact

- Website: [pyxis3.ai](https://pyxis3.ai)
- Email: [ops@pyxis3.ai](mailto:ops@pyxis3.ai)
- LinkedIn: [/company/pyxis3](https://www.linkedin.com/company/pyxis3)
- Founder: [Omar Abdrabo (@oabdrabo)](https://github.com/oabdrabo)

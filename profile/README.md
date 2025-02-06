# PYXIS3


**Model-agnostic LLM serving infrastructure**, the Kubernetes-native control plane that lets enterprises run open-weight language models in production without locking into a single cloud, model vendor, or inference runtime.


The category did not exist as a named sub-segment of AI infrastructure five years ago. Today it is one of the most strategically contested layers of the enterprise AI stack, and the UK does not yet have a domestic leader in it.


## Why we exist


Production LLM deployment in 2026 faces three independent forms of lock-in:


1. **Cloud lock-in**: your inference fleet lives on one cloud's GPUs (AWS, GCP, Azure). Moving a model means re-implementing the serving stack.
2. **Model-vendor lock-in**: your control plane is bound to one MLOps platform. Moving means losing audit, lineage, and fair-share scheduling.
3. **Runtime lock-in**: your model is wired to one inference runtime (vLLM, TGI, Triton, SGLang). Moving means re-tuning latency and throughput from scratch.


Each lock-in is independent. Each has a different cost to break. None of the existing platforms solves all three. **PYXIS3 is the operations layer that lets you mix and match.** The same control plane drives the same models on the same KPIs across heterogeneous fleets: cloud, on-prem, mixed.


## Public repositories


| Repository | Purpose |
|---|---|
| [`pyxis-arch`](https://github.com/pyxis3-ai/pyxis-arch) | Architecture thesis covering Funnel-Engine-Lens, runtime-adapter abstraction, fair-share GPU scheduling, and audit/lineage across runtime migration. |
| [`vllm-bench`](https://github.com/pyxis3-ai/vllm-bench) | TTFT and TPOT benchmarking for OpenAI-compatible inference endpoints across vLLM, TGI, llama.cpp, and Ollama. |
| [`llm-serving-cookbook`](https://github.com/pyxis3-ai/llm-serving-cookbook) | Production recipes for Kubernetes-native vLLM serving: vLLM on EKS, KEDA autoscaling, token economics, TTFT optimisation, runtime selection. |
| [`lens`](https://github.com/pyxis3-ai/lens) | In-cluster Kubernetes observability with LLM-endpoint discovery for vLLM, TGI, llama.cpp, and Ollama. In-browser `kubectl exec`. Live at [`lens.pyxis3.ai`](https://lens.pyxis3.ai). |
| [`noor`](https://github.com/pyxis3-ai/noor) | Multilingual AI semantic search over the Qur'an and classical Arabic literature. Sentence-Transformers and sqlite-vec. Live at [`noor.pyxis3.ai`](https://noor.pyxis3.ai). |
| [`awesome-model-agnostic-llm`](https://github.com/pyxis3-ai/awesome-model-agnostic-llm) | Curated index of model-agnostic LLM tooling: serving runtimes, routers, evaluators, and standards. |


## Contact


- Website: [pyxis3.ai](https://pyxis3.ai)
- Email: [ops@pyxis3.ai](mailto:ops@pyxis3.ai)
- LinkedIn: [/company/pyxis3](https://www.linkedin.com/company/pyxis3)
- Founder: [Omar Abdrabo (@oabdrabo)](https://github.com/oabdrabo)

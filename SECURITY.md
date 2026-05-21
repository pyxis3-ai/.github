# Security Policy

## Reporting a vulnerability

If you discover a security issue in any PYXIS3 repository, **please do not open a public issue**. Instead, email [ops@pyxis3.ai](mailto:ops@pyxis3.ai) with:

- A description of the issue
- A reproducer (proof-of-concept code, exploitation steps)
- Your assessment of impact

We aim to acknowledge within 48 hours and propose a fix or mitigation within 14 days for in-scope issues.

## Scope

In scope:
- Authentication / authorization bypass in `lens` (the only PYXIS3 project that hosts a web surface)
- Code-injection vulnerabilities in `vllm-bench` (the only one that runs user-supplied benchmarks)
- Supply-chain issues — typo-squatted dependencies, malicious upstream packages

Out of scope:
- Issues in upstream projects (vLLM, TGI, Triton, etc.) — please report those upstream
- DoS attacks against publicly hosted demos (`noor.pyxis3.ai`, `lens.pyxis3.ai`) — these are demo instances, not production
- Issues in documentation repos (`pyxis-arch`, `awesome-model-agnostic-llm`, `llm-serving-cookbook`)

## Disclosure

We follow coordinated disclosure. After a fix is released, we credit the reporter (with permission) in the release notes.

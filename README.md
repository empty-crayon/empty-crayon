## Hi, I'm Chinmay 👋

I'm an ML Engineer focused on <u>LLM inference performance, systems level optimisation and LLM post-training</u>. I also write about what I learn at [Gradient Update](https://gradientupdate.substack.com).

[![Substack](https://img.shields.io/badge/Gradient%20Update-Substack-orange?style=flat-square&logo=substack)](https://gradientupdate.substack.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/chinmay-prakash/)
[![Email](https://img.shields.io/badge/Email-iamchinmayp@gmail.com-red?style=flat-square&logo=gmail)](mailto:iamchinmayp@gmail.com)

---
### Some of my recent work:

- **[nano-serve](https://github.com/empty-crayon/nano-serve)** — OpenAI-compatible inference gateway with SSE streaming, per-request TTFT/TPOT/inter-chunk timing, and Prometheus & Grafana for observability.

    > Includes a [deep-dive experiment](https://github.com/empty-crayon/nano-serve/blob/main/deep-dive.md) running ablations on prefix caching and speculative deccoding (MPT) for running agentic workloads; With Qwen3.5-4B on A10 GPU, achieving 56% TTFT reduction and 58% throughput improvement.
- **[how-fast:](https://github.com/empty-crayon/how-fast)** — Async LLM benchmarking CLI. Closed-loop and open-loop modes, SLO pass/fail per workload, GPU telemetry sidecar.


- **[moe-from-scratch](https://github.com/empty-crayon/moe-from-scratch-and-upcycling)** — Llama-style MoE decoder: RoPE, GQA, top-K routing, SwiGLU, load-balancing loss. Extended to BTX via sparse upcycling with three domain experts.
---

### Writing

| Topic | Link |
|-------|------|
| GQA from First Principles | [Read](https://gradientupdate.substack.com/p/implementing-the-modern-llm-stack-c4d) |
| GPU Mental Models for Beginners | [Read](https://gradientupdate.substack.com/p/gpu-mental-models-for-beginners) |
| Constrained Decoding: How LLMs Generate Valid JSON | [Read](https://gradientupdate.substack.com/p/constrained-decoding-how-llms-generate) |
---

### What's Next

I believe the most interesting problems are moving to the hardware-software co-design layer. Right now I'm specifically working toward:

- Learning to write custom CUDA kernels for attention and quantized matmuls
- Building a distributed pipelines for training and inference
- Exploring model adaptation for non-GPU accelerators

If you're working on any of these - I'd love to talk!

---


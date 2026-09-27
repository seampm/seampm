# Peter Seam

Software engineer. I like understanding systems all the way down — most recently by writing an LLM inference engine from scratch in C++.

## 🔧 tinyinfer

**[seampm/tinyinfer](https://github.com/seampm/tinyinfer)** — a from-scratch inference engine for Llama models: hand-rolled file parser, BPE tokenizer, AVX2 vector math, int8 quantization. Zero ML dependencies, ~1,700 lines of C++20.

Benchmarked head-to-head with llama.cpp: **101%** of its throughput on a 15M model, **74%** on a 1.1B model — with the methodology published in the repo.

▶️ **[Try the live demo](https://seampm.github.io/tinyinfer/)** — terminal replay, benchmark charts, architecture walkthrough. No setup required.

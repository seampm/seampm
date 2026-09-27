# Peter Seam

Software engineer working with C++, systems, and performance. I like understanding everything from low-level code to high level projects.

## What I've been building

**tinyinfer** — an LLM inference engine written from scratch in C++: hand-rolled file parser, tokenizer, vector math kernels, and quantization. No frameworks, no copied code. It matches llama.cpp's throughput on a 15M-parameter model.

- [Code](https://github.com/seampm/tinyinfer) · [Live demo](https://seampm.github.io/tinyinfer/)

**tinytrain** — a neural network training framework written from scratch in C++: reverse-mode autograd, AdamW, and a Llama transformer. It trains models that run in tinyinfer — the full LLM loop, no PyTorch.

- [Code](https://github.com/seampm/tinytrain) · [Live demo](https://seampm.github.io/tinytrain/)

**tinystore** — a distributed key-value store written from scratch in C++: epoll networking, consistent hashing, async replication, heartbeat failover. 150k ops/sec single-node; a 3-node cluster survives kill -9.

- [Code](https://github.com/seampm/tinystore) · [Live demo](https://seampm.github.io/tinystore/)

**pymatch** — a limit order book matching engine written from scratch in Python: price-time priority matching, an exchange simulator with latency and fees, and an event-driven backtester. 400k orders/sec, 23 tests.

- [Code](https://github.com/seampm/pymatch) · [Live demo](https://seampm.github.io/pymatch/)

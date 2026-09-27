# Peter Seam

Software engineer working close to the metal — C++, systems, and performance. I like understanding things all the way down; when the docs run out, I read the source.

## What I've been building

**tinyinfer** — an LLM inference engine written from scratch in C++: hand-rolled file parser, tokenizer, vector math kernels, and quantization. No frameworks, no copied code. It matches llama.cpp's throughput on a 15M-parameter model.

- [Code](https://github.com/seampm/tinyinfer) · [Live demo](https://seampm.github.io/tinyinfer/)

**tinytrain** — a neural network training framework written from scratch in C++: reverse-mode autograd, AdamW, and a Llama transformer. It trains models that run in tinyinfer — the full LLM loop, no PyTorch.

- [Code](https://github.com/seampm/tinytrain) · [Live demo](https://seampm.github.io/tinytrain/)

**pymatch** — a limit order book matching engine written from scratch in Python: price-time priority matching, an exchange simulator with latency and fees, and an event-driven backtester. 400k orders/sec, 23 tests.

- [Code](https://github.com/seampm/pymatch) · [Live demo](https://seampm.github.io/pymatch/)

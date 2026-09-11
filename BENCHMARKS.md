# EdgeRuntimeHQ Edge AI Inference Latency & Memory Leaderboard

Empirical Time-To-First-Token (TTFT), tokens/second throughput, and memory consumption across WebGPU in-browser runtimes, ONNX Runtime Web, and Edge serverless.

⚡ **Live Inference Leaderboard:** [https://edgeruntimehq.pages.dev/](https://edgeruntimehq.pages.dev/)

## 1. In-Browser WebGPU LLM Inference (M3 MacBook Pro / RTX 4080)

| Model & Size | Runtime | Time To First Token (TTFT) | Output Throughput | Memory Footprint |
| :--- | :--- | :--- | :--- | :--- |
| Llama-3.2 1B (Q4) | WebGPU (Wasm SIMD) | 120 ms | 48.5 tok/s | 820 MB |
| SmolLM2 360M (Q4) | WebGPU (Wasm SIMD) | 45 ms | 112.0 tok/s | 310 MB |
| Whisper-Tiny (FP16) | ONNX Runtime Web | 210 ms | 18.2x Realtime | 450 MB |

---
Maintained by [EdgeRuntimeHQ](https://edgeruntimehq.pages.dev/).

## 📚 In-Depth Technical Implementation Guides

| Target Engineering Query | Production Reference & Guide URL |
| :--- | :--- |
| **Webgpu Vs Wasm Llm Inference Benchmark** | [https://edgeruntimehq.pages.dev/webgpu-vs-wasm-in-browser-llm-inference-benchmarks/](https://edgeruntimehq.pages.dev/webgpu-vs-wasm-in-browser-llm-inference-benchmarks/) |
| **Onnx Runtime Vs Tensorrt Edge Latency** | [https://edgeruntimehq.pages.dev/onnx-runtime-vs-tensorrt-edge-server-latency/](https://edgeruntimehq.pages.dev/onnx-runtime-vs-tensorrt-edge-server-latency/) |
| **Webgpu Fp16 Vs Fp32 Browser Inference Speed** | [https://edgeruntimehq.pages.dev/webgpu-fp16-vs-fp32-benchmark/](https://edgeruntimehq.pages.dev/webgpu-fp16-vs-fp32-benchmark/) |
| **Smollm2 360M Webgpu Memory Footprint** | [https://edgeruntimehq.pages.dev/smollm2-360m-webgpu-guide/](https://edgeruntimehq.pages.dev/smollm2-360m-webgpu-guide/) |


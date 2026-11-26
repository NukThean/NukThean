### NukThean

Building open-source Khmer speech recognition (ASR) models, cleaned Khmer datasets, and offline inference tools.

#### Featured Project — Krama Khmer ASR

An open-source (`Apache-2.0`) Khmer speech-to-text model (`343.4M` parameters) trained on `1,568.77 hours` across 8 domains for offline CPU, GPU, and client-side browser inference.

| Resource | Link | Details |
|---|---|---|
| **GitHub (Inference & Web Demo)** | [`NukThean/krama-asr-khmer`](https://github.com/NukThean/krama-asr-khmer) | Standalone `krama_onnx.py`, `krama_asr.py`, and self-hostable `onnxruntime-web` app |
| **PyTorch Weights** | [`Nukthean/krama-asr-khmer`](https://huggingface.co/Nukthean/krama-asr-khmer) | `658.2 MiB` `bfloat16` SafeTensors (`6.32%` FLEURS test / `2.69%` unseen iAny Beam-5 CER) |
| **Offline CPU ONNX INT8** | [`Nukthean/krama-asr-khmer-onnx`](https://huggingface.co/Nukthean/krama-asr-khmer-onnx) | `358.3 MiB` dynamic INT8, zero PyTorch (`0.188 s/clip` Greedy on desktop CPU) |
| **Live Browser Demo** | [`Nukthean/krama-asr-khmer-demo`](https://huggingface.co/spaces/Nukthean/krama-asr-khmer-demo) | Runs 100% client-side in your browser via WASM (no server) |
| **Cleaned Khmer Corpus** | [`Nukthean/krama-asr-khmer-corpus`](https://huggingface.co/datasets/Nukthean/krama-asr-khmer-corpus) | `1,543.80 h` cleaned & audio-verified Khmer ASR dataset |

- **Hugging Face:** [huggingface.co/Nukthean](https://huggingface.co/Nukthean)
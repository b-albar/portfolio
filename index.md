# Portfolio
---
## FAT5 - T5 with Flash Attention 2

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/flashT5)

<div style="text-align: justify">FAT5 is an implementation of T5 in PyTorch with an UL2 objective optimized for GPGPU.
It uses custom CUDA kernels and specific optimizations to increase throughput and reduce memory usage for both training and inference by a factor of 4.
This code was used to pretrained several models in French in sizes ranging from 147M parameters to 1B parameters using 2 Nvidia A100. Weights will soon be released on Hugging Face
</div>

## QAmemBERT

[![View on Hugging Face](https://huggingface.co/datasets/huggingface/badges/resolve/main/model-on-hf-md.svg)](https://huggingface.co/CATIE-AQ/QAmembert)

<div style="text-align: justify">QAmemBERT is a state-of-the-art question-answering model in French and,
contrary to previously existing models in French, it support questions where the answer is not contained
in the context. It is available in two sizes ([base](https://huggingface.co/CATIE-AQ/QAmembert) and
[large](https://huggingface.co/CATIE-AQ/QAmembert-large))
and is freely available on Hugging Face. It was developed in collaboration with [Loïck Bourdois](https://lbourdois.github.io/) and [Pierre Bédu](https://fr.linkedin.com/in/pierre-b%C3%A9du-13141513b).
</div>

## Triton-rs

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/triton-rust)


<div style="text-align: justify">
Triton-rs i a Rust gRPC client library for [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server).
It also supports passing tensor through the system shared memory for fast local inference.
</div>

---

## Few/zero shot for the French language

[![View on YouTube](https://img.shields.io/badge/YouTube-View_on_YouTube-red?logo=YouTube)](https://www.youtube.com/watch?v=vhHkASBRRP4)

<div style="text-align: justify">
This conference (in French) was given for DataQuitaine 2023 and present various benchmarks for few and zero-shot learning on various French classical NLP tasks.
</div>

---

## CTC Beam search in Rust

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/rustlm)

A fast CTC beam search decoder supporting various language models using the previously featured Triton-rs,
coded in Rust. Used for fast decoding with a speech-to-text model in French.
<div style="text-align: justify"></div>

---

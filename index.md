# Portfolio
---

## Machete

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/b-albar/machete)

Machete provides a simple and optimized way to design megakernels in CuteDSL, speeding up inference and training of models.

---

## Cutedsl-trace

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/b-albar/cutedsl-trace)

A GPU kernel tracing library for CuteDSL providing  nanosecond-resolution timestamps with low-overhead.

---

## Techne

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/b-albar/techne)

**Abstract tool-augmented reinforcement learning framework for LLMs.**
Techne is a framework to research new distillation and training agentic language models with multi-turn tool use. It features multi-algorithm training (PPO, GRPO), and efficient distributed training.

---

## FAT5 - T5 with Flash Attention 2

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/flashT5)

FAT5 is an implementation of T5 in PyTorch with an UL2 objective optimized for GPGPU.
It uses custom CUDA kernels and specific optimizations to increase throughput and reduce memory usage for both training and inference by a factor of 4.
This code was used to pretrained several models in French in sizes ranging from 147M parameters to 2.5B parameters using only 2 Nvidia A100 from 300M documents from [CulturaX-fr](https://huggingface.co/datasets/uonlp/CulturaX). Weights will soon be released on Hugging Face as well as adapted Flan-T5 weights.

---

## QAmemBERT

[![View on Hugging Face](https://huggingface.co/datasets/huggingface/badges/resolve/main/model-on-hf-md.svg)](https://huggingface.co/CATIE-AQ/QAmembert)

QAmemBERT is a state-of-the-art question-answering model in French and,
contrary to previously existing models in French, it support questions where the answer is not contained
in the context. It is available in two sizes ([base](https://huggingface.co/CATIE-AQ/QAmembert) and
[large](https://huggingface.co/CATIE-AQ/QAmembert-large))
and is freely available on Hugging Face. It was developed in collaboration with [Loïck Bourdois](https://lbourdois.github.io/) and [Pierre Bédu](https://fr.linkedin.com/in/pierre-b%C3%A9du-13141513b).

---

## Triton-rs

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/triton-rust)

Triton-rs is a Rust gRPC client library for [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server).
It also supports passing tensor through the system shared memory for fast local inference.

---

## Few/zero shot for the French language

[![View on YouTube](https://img.shields.io/badge/YouTube-View_on_YouTube-red?logo=YouTube)](https://www.youtube.com/watch?v=vhHkASBRRP4)

This conference (in French) was given for DataQuitaine 2023 and present various benchmarks for few and zero-shot learning on various French classical NLP tasks.

---

## CTC Beam search in Rust

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/catie-aq/rustlm)

A fast CTC beam search decoder supporting various language models using the previously featured Triton-rs,
coded in Rust. Used for fast decoding with a speech-to-text model in French.

---

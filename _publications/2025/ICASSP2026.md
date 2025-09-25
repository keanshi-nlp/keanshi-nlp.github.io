---
title:          "Sparse Training Scheme for Multimodal LLM"
date:           2025-09-18 00:01:00 +0800
selected:       true
pub:            "arXiv"
# pub_pre:        "Submitted to ICASSP'2026"
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Multimodal Large Language Models (MLLMs) have demonstrated outstanding performance across a variety of domains. However, training MLLMs is often inefficient due to the significantly longer input sequences introduced by multimodal data and the low utilization of inter-layer computations. To address this challenge, we shift the focus to the training process itself and propose a novel training-efficient framework based on sparse representations, termed the Sparse Training Scheme (STS). This scheme consists of two key components: the Visual Token Compressor, which reduces the information load by compressing visual tokens, and the Layer Dynamic Skipper, which mitigates the computational overhead by dynamically skipping unnecessary layers in the language model during both forward and backward passes. Our approach is broadly applicable to diverse MLLM architectures and has been extensively evaluated on multiple benchmarks, demonstrating its effectiveness and efficiency.
cover:          /assets/images/covers/STS.png
authors:
  - Kean Shi
  - Liang Chen
  - Haozhe Zhao
  - Baobao Chang
links:
  Paper: https://arxiv.org/abs/2509.18150
---

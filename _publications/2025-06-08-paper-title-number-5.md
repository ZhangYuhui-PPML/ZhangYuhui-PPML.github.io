---
title: "03-Comet: Accelerating Private Inference for Large Language Model by Predicting Activation Sparsity"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'With the growing use of large language models (LLMs) hosted on cloud platforms to offer inference services, privacy concerns about the potential leakage of sensitive information are escalating. Secure Multi-Party Computation (MPC) is a promising solution to protect the privacy in LLM inference. However, MPC requires frequent inter-server communication, causing high performance overhead. Inspired by the prevalent activation sparsity of LLMs, where most neuron are not activated after non-linear activation functions, we propose an efficient private inference system, Comet. This system employs an accurate and fast predictor to predict the sparsity distribution of activation function output. Additionally, we introduce a new private inference protocol. It efficiently and securely avoids computations involving zero values by exploiting the spatial locality of the predicted sparsity distribution. While this computation-avoidance approach impacts the spatiotemporal continuity of KV cache entries, we address this challenge with a low-communication overhead cache refilling strategy that merges miss requests and incorporates a prefetching mechanism. Finally, we evaluate Comet on four common LLMs and compare it with six state-of-the-art private inference systems. Comet achieves a 1.87×−2.63× speedup and a 1.94×−2.64× communication reduction.'
date: 2024-02-17
venue: 'GitHub Journal of Bugs'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11023441'
citation: 'Yan G, Zhang Y, Guo Z, et al. Comet: Accelerating Private Inference for Large Language Model by Predicting Activation Sparsity[C]//2025 IEEE Symposium on Security and Privacy (SP). IEEE, 2025: 2827-2845.'
---

Using [MathJax](https://www.mathjax.org/) in the description is supported - $$E=mc^2$$ - however, the use must be mindful that the default delimiters are `$$...$$` and `\\[...\\]` which differs from the `$...$` that is typically expected.

---
title: "TPP-LLM: Modeling Temporal Point Processes by Efficiently Fine-Tuning Large Language Models"
authors: "<b>Zefang Liu</b>, Yinzhu Quan"
collection: publications
category: conferences
permalink: /publication/liu2024tpp
excerpt: 'This paper introduces TPP-LLM, a framework that integrates large language models with temporal embeddings to improve event sequence modeling and prediction, demonstrating strong performance across multiple real-world datasets.'
date: 2024-10-01
venue: 'ICLR 2025 Workshop on Foundation Models in the Wild (FM-Wild)'
paperurl: 'https://arxiv.org/abs/2410.02062'
codeurl: 'https://github.com/zefang-liu/TPP-LLM'
dataurl: 'https://huggingface.co/tppllm'
posterurl: /files/liu2024tpp_poster.pdf
confurl: 'https://fm-wild-community.github.io/'
citation: 'Liu, Zefang and Quan, Yinzhu. &quot;TPP-LLM: Modeling Temporal Point Processes by Efficiently Fine-Tuning Large Language Models.&quot; <i>arXiv preprint arXiv:2410.02062</i> (2024).'
---

**Abstract**

Temporal point processes (TPPs) are widely used to model the timing and occurrence of events in domains such as social networks, transportation systems, and e-commerce. In this paper, we introduce TPP-LLM, a novel framework that integrates large language models (LLMs) with TPPs to capture both the semantic and temporal aspects of event sequences. Unlike traditional methods that rely on categorical event type representations, TPP-LLM directly utilizes the textual descriptions of event types, enabling the model to capture rich semantic information embedded in the text. While LLMs excel at understanding event semantics, they are less adept at capturing temporal patterns. To address this, TPP-LLM incorporates temporal embeddings and employs parameter-efficient fine-tuning (PEFT) methods to effectively learn temporal dynamics without extensive retraining. This approach improves both predictive accuracy and computational efficiency. Experimental results across diverse real-world datasets demonstrate that TPP-LLM outperforms state-of-the-art baselines in sequence modeling and event prediction, highlighting the benefits of combining LLMs with TPPs.

---
title: "Retrieval of Temporal Event Sequences from Textual Descriptions"
authors: "<b>Zefang Liu</b>, Yinzhu Quan"
collection: publications
category: conferences
permalink: /publication/liu2024retrieval
excerpt: 'We present TESRBench, a benchmark for retrieving temporal event sequences from descriptions, and TPP-Embedding, a model aligning sequences and descriptions in a shared embedding space, achieving state-of-the-art performance on TESRBench.'
date: 2024-10-15
venue: 'NAACL 2025 Workshop on Knowledge-Augmented Methods for NLP (KnowledgeNLP)'
paperurl: 'https://arxiv.org/abs/2410.14043'
codeurl: 'https://github.com/zefang-liu/TPP-Embedding'
dataurl: 'https://huggingface.co/tppllm'
posterurl: /files/liu2024retrieval.pdf
citation: 'Liu, Zefang and Quan, Yinzhu. &quot;Retrieval of Temporal Event Sequences from Textual Descriptions.&quot; <i>arXiv preprint arXiv:2410.14043</i> (2024).'
---

**Abstract**

Retrieving temporal event sequences from textual descriptions is crucial for applications such as analyzing e-commerce behavior, monitoring social media activities, and tracking criminal incidents. To advance this task, we introduce TESRBench, a comprehensive benchmark for temporal event sequence retrieval (TESR) from textual descriptions. TESRBench includes diverse real-world datasets with synthesized and reviewed textual descriptions, providing a strong foundation for evaluating retrieval performance and addressing challenges in this domain. Building on this benchmark, we propose TPP-Embedding, a novel model for embedding and retrieving event sequences. The model leverages the TPP-LLM framework, integrating large language models (LLMs) with temporal point processes (TPPs) to encode both event texts and times. By pooling representations and applying a contrastive loss, it unifies temporal dynamics and event semantics in a shared embedding space, aligning sequence-level embeddings of event sequences and their descriptions. TPP-Embedding demonstrates superior performance over baseline models across TESRBench datasets, establishing it as a powerful solution for the temporal event sequence retrieval task.

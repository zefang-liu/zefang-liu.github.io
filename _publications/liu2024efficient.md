---
title: "Efficient Retrieval of Temporal Event Sequences from Textual Descriptions"
authors: "<b>Zefang Liu</b>, Yinzhu Quan"
collection: publications
category: conferences
permalink: /publication/liu2024efficient
excerpt: 'We propose TPP-LLM-Embedding, a model that combines temporal and event-type information for efficient retrieval of event sequences from textual descriptions, outperforming baseline models across diverse datasets.'
date: 2024-10-15
venue: 'arXiv preprint arXiv:2410.14043'
paperurl: 'https://arxiv.org/abs/2410.14043'
codeurl: 'https://github.com/zefang-liu/TPP-LLM-Embedding'
dataurl: 'https://huggingface.co/tppllm'
citation: 'Liu, Zefang and Quan, Yinzhu. &quot;Efficient Retrieval of Temporal Event Sequences from Textual Descriptions.&quot; <i>arXiv preprint arXiv:2410.14043</i> (2024).'
---

**Abstract**

Retrieving temporal event sequences from textual descriptions is essential for applications such as analyzing e-commerce behavior, monitoring social media activities, and tracking criminal incidents. In this paper, we introduce TPP-LLM-Embedding, a unified model for efficiently embedding and retrieving event sequences based on natural language descriptions. Built on the TPP-LLM framework, which integrates large language models with temporal point processes, our model encodes both event types and times, generating a sequence-level representation through pooling. Textual descriptions are embedded using the same architecture, ensuring a shared embedding space for both sequences and descriptions. We optimize a contrastive loss based on similarity between these embeddings, bringing matching pairs closer and separating non-matching ones. TPP-LLM-Embedding enables efficient retrieval and demonstrates superior performance compared to baseline models across diverse datasets.

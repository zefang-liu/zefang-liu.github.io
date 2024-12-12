---
title: "AdaMoLE: Fine-Tuning Large Language Models with Adaptive Mixture of Low-Rank Adaptation Experts"
authors: "<b>Zefang Liu</b>, Jiahua Luo"
collection: publications
category: conferences
permalink: /publication/liu2024adamole
excerpt: 'AdaMoLE introduces a dynamic approach to fine-tuning LLMs by using an adaptive mixture of LoRA experts, outperforming traditional top-k routing methods in various tasks.'
date: 2024-05-01
venue: '2024 Conference on Language Modeling (COLM)'
paperurl: 'https://arxiv.org/abs/2405.00361'
codeurl: 'https://github.com/zefang-liu/AdaMoLE'
posterurl: 'https://github.com/zefang-liu/AdaMoLE/blob/main/poster.pdf'
citation: 'Liu, Zefang and Luo, Jiahua. &quot;AdaMoLE: Fine-Tuning Large Language Models with Adaptive Mixture of Low-Rank Adaptation Experts.&quot; <i>COLM 2024</i> (2024).'
---

**Abstract**

We introduce AdaMoLE, a novel method for fine-tuning large language models (LLMs) through an Adaptive Mixture of Low-Rank Adaptation (LoRA) Experts. Moving beyond conventional methods that employ a static top-k strategy for activating experts, AdaMoLE dynamically adjusts the activation threshold using a dedicated threshold network, adaptively responding to the varying complexities of different tasks. By replacing a single LoRA in a layer with multiple LoRA experts and integrating a gating function with the threshold mechanism, AdaMoLE effectively selects and activates the most appropriate experts based on the input context. Our extensive evaluations across a variety of commonsense reasoning and natural language processing tasks show that AdaMoLE exceeds baseline performance. This enhancement highlights the advantages of AdaMoLE's adaptive selection of LoRA experts, improving model effectiveness without a corresponding increase in the expert count. The experimental validation not only confirms AdaMoLE as a robust approach for enhancing LLMs but also suggests valuable directions for future research in adaptive expert selection mechanisms, potentially broadening the scope for optimizing model performance across diverse language processing tasks.

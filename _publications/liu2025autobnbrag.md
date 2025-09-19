---
title: "AutoBnB-RAG: Enhancing Multi-Agent Incident Response with Retrieval-Augmented Generation"
authors: "<b>Zefang Liu</b>, Arman Anwar"
collection: publications
category: conferences
permalink: /publication/liu2025autobnbrag
excerpt: 'AutoBnB-RAG adds retrieval-augmented generation to multi-agent incident response, improving coordination and decision-making in cyber incident simulations.'
date: 2025-08-18
venue: 'ICDM 2025 Workshop on the use of Large Language Models for Cybersecurity (LLM4Sec)'
paperurl: 'https://arxiv.org/abs/2508.13118'
codeurl: 'https://github.com/zefang-liu/AutoBnB'
confurl: 'https://llm4sec-workshop.github.io/index'
citation: 'Liu, Zefang and Anwar, Arman. &quot;AutoBnB-RAG: Enhancing Multi-Agent Incident Response with Retrieval-Augmented Generation.&quot; <i>arXiv preprint arXiv:2508.13118</i> (2025).'

---

**Abstract**

Incident response (IR) requires fast, coordinated, and well-informed decision-making to contain and mitigate cyber threats. While large language models (LLMs) have shown promise as autonomous agents in simulated IR settings, their reasoning is often limited by a lack of access to external knowledge. In this work, we present AutoBnB-RAG, an extension of the AutoBnB framework that incorporates retrieval-augmented generation (RAG) into multi-agent incident response simulations. Built on the Backdoors & Breaches (B&B) tabletop game environment, AutoBnB-RAG enables agents to issue retrieval queries and incorporate external evidence during collaborative investigations. We introduce two retrieval settings: one grounded in curated technical documentation (RAG-Wiki), and another using narrative-style incident reports (RAG-News). We evaluate performance across eight team structures, including newly introduced argumentative configurations designed to promote critical reasoning. To validate practical utility, we also simulate real-world cyber incidents based on public breach reports, demonstrating AutoBnB-RAG's ability to reconstruct complex multi-stage attacks. Our results show that retrieval augmentation improves decision quality and success rates across diverse organizational models. This work demonstrates the value of integrating retrieval mechanisms into LLM-based multi-agent systems for cybersecurity decision-making.

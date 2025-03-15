---
title: "Enhancing QA over Scholarly Knowledge Graphs: Addressing Semantic and Structural Challenges"
collection: talks
type: "Poster"
venue: "ELLIS workshop on Representation Learning and Generative Models for Structured Data"
date: 2025-02-27
location: "Amsterdam, NL"
---

[Poster Download](https://drive.google.com/file/d/1Cyjtbg_SNx_uablnFI7AAov0mj1iG7tk/view?usp=sharing)\
[ELLIS workshop website](https://sites.google.com/view/rl-and-gm-for-sd/home)\
Abstract: Scholarly knowledge graphs (SKGs) capture bibliographic metadata and scientific elements such as research problems, theories, and evaluations. Question answering (QA) over SKGs is challenging due to the complexity of scholarly data and the intricate structure of SKGs. This task involves generating SPARQL queries from natural language questions (NLQs), but large language models (LLMs) face limitations in this task, struggling with correct entity and relation linking due to their lack of knowledge about the content of SKGs and insufficient understanding of their ontological schema, particularly in low-resource SKGs like the Open Research Knowledge Graph (ORKG).

Insights from a pilot experiment using ChatGPT(GPT-4) to generate SPARQL queries for handcrafted questions in the SciQA Benchmark reveal two primary error types: semantic inaccuracies, where incorrect entities or properties are linked despite correct query structure, and structural inconsistencies, involving errors in query structure, such as missing or abundant links (triples). To address these issues, we propose a retrieval-augmented generation (RAG) approach, providing LLMs with top-k candidate entities and properties from ORKG as context. Additionally, fine-tuning LLMs with NL-SPARQL pairs and/or ORKG triples enhances their ability to generate accurate, multi-hop SPARQL queries. Additionally, traditional evaluation metrics like BLEU and ROUGE rely on n-gram token overlap and fail to detect semantic issues in generated queries, leading to high scores despite low execution accuracy when queries contain incorrect properties or entities. We propose a nuanced metric that considers both semantic and structural accuracy. We conduct experiments on the SciQA Benchmark and compare our results with baselines and state-of-the-art methods.


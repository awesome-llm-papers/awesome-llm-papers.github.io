---
layout: publication
title: Literary Evidence Retrieval Via Long-context Language Models
authors: Thai Katherine, Iyyer Mohit
conference: Transactions of the Association for Computational Linguistics
year: 2025
bibkey: thai2025literary
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.03090'}]
tags: [Evaluation, ACL, TACL, RAG, Datasets]
---
How well do modern long-context language models understand literary fiction? We explore this question via the task of literary evidence retrieval, repurposing the RELiC dataset of That et al. (2022) to construct a benchmark where the entire text of a primary source (e.g., The Great Gatsby) is provided to an LLM alongside literary criticism with a missing quotation from that work. This setting, in which the model must generate the missing quotation, mirrors the human process of literary analysis by requiring models to perform both global narrative reasoning and close textual examination. We curate a high-quality subset of 292 examples through extensive filtering and human verification. Our experiments show that recent reasoning models, such as Gemini Pro 2.5 can exceed human expert performance (62.5% vs. 50% accuracy). In contrast, the best open-weight model achieves only 29.1% accuracy, highlighting a wide gap in interpretive reasoning between open and closed-weight models. Despite their speed and apparent accuracy, even the strongest models struggle with nuanced literary signals and overgeneration, signaling open challenges for applying LLMs to literary analysis. We release our dataset and evaluation code to encourage future work in this direction.
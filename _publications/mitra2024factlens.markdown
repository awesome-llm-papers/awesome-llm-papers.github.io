---
layout: publication
title: 'Factlens: Benchmarking Fine-grained Fact Verification'
authors: Mitra et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: mitra2024factlens
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.05980'}]
tags: [Datasets, Ethics And Bias, ACL, Evaluation]
---
Large Language Models (LLMs) have shown impressive capability in language generation and understanding, but their tendency to hallucinate and produce factually incorrect information remains a key limitation. To verify LLM-generated contents and claims from other sources, traditional verification approaches often rely on holistic models that assign a single factuality label to complex claims, potentially obscuring nuanced errors. In this paper, we advocate for a shift towards fine-grained verification, where complex claims are broken down into smaller sub-claims for individual verification, allowing for more precise identification of inaccuracies, improved transparency, and reduced ambiguity in evidence retrieval. However, generating sub-claims poses challenges, such as maintaining context and ensuring semantic equivalence with respect to the original claim. We introduce FactLens, a benchmark for evaluating fine-grained fact verification, with metrics and automated evaluators of sub-claim quality. The benchmark data is manually curated to ensure high-quality ground truth. Our results show alignment between automated FactLens evaluators and human judgments, and we discuss the impact of sub-claim characteristics on the overall verification performance.
---
layout: publication
title: Large Language Models For Data Synthesis
authors: Yihong Tang, Menglin Kong, Lijun Sun
conference: No Venue
year: 2025
bibkey: tang2025large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.14752'}]
tags: ["Datasets", "Efficiency", "Privacy", "Tools"]
short_authors: Yihong Tang, Menglin Kong, Lijun Sun
---
Generating synthetic data that faithfully captures the statistical structure of real-world distributions is a fundamental challenge in data modeling. Classical approaches often depend on strong parametric assumptions or manual structural design and struggle in high-dimensional or heterogeneous domains. Recent progress in Large Language Models (LLMs) reveals their potential as flexible, high-dimensional priors over real-world distributions. However, when applied to data synthesis, standard LLM-based sampling is inefficient, constrained by fixed context limits, and fails to ensure statistical alignment. Given this, we introduce LLMSynthor, a general framework for data synthesis that transforms LLMs into structure-aware simulators guided by distributional feedback. LLMSynthor treats the LLM as a nonparametric copula simulator for modeling high-order dependencies and introduces LLM Proposal Sampling to generate grounded proposal distributions that improve sampling efficiency without requiring rejection. By minimizing discrepancies in the summary statistics space, the iterative synthesis loop aligns real and synthetic data while gradually uncovering and refining the latent generative structure. We evaluate LLMSynthor in both controlled and real-world settings using heterogeneous datasets in privacy-sensitive domains (e.g., e-commerce, population, and mobility) that encompass both structured and unstructured formats. The synthetic data produced by LLMSynthor shows high statistical fidelity, practical utility, and cross-data adaptability, positioning it as a valuable tool across economics, social science, urban studies, and beyond.

https://huggingface.co/discussions/paper/6832c2c9ba29b909f4013aea
---
layout: publication
title: 'Polyglotoxicityprompts: Multilingual Evaluation Of Neural Toxic Degeneration
  In Large Language Models'
authors: Jain et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2024
bibkey: jain2024polyglotoxicityprompts
citations: 179
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.09373'}]
tags: [Prompting, Tools, Evaluation, ACL, EMNLP, RAG, Datasets, Responsible AI, Alt]
---
Recent advances in large language models (LLMs) have led to their extensive
global deployment, and ensuring their safety calls for comprehensive and
multilingual toxicity evaluations. However, existing toxicity benchmarks are
overwhelmingly focused on English, posing serious risks to deploying LLMs in
other languages. We address this by introducing PolygloToxicityPrompts (PTP),
the first large-scale multilingual toxicity evaluation benchmark of 425K
naturally occurring prompts spanning 17 languages. We overcome the scarcity of
naturally occurring toxicity in web-text and ensure coverage across languages
with varying resources by automatically scraping over 100M web-text documents.
Using PTP, we investigate research questions to study the impact of model size,
prompt language, and instruction and preference-tuning methods on toxicity by
benchmarking over 60 LLMs. Notably, we find that toxicity increases as language
resources decrease or model size increases. Although instruction- and
preference-tuning reduce toxicity, the choice of preference-tuning method does
not have any significant impact. Our findings shed light on crucial
shortcomings of LLM safeguarding and highlight areas for future research.
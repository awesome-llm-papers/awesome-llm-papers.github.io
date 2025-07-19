---
layout: publication
title: 'VALUE: Value-aware Large Language Model For Query Rewriting Via Weighted Trie
  In Sponsored Search'
authors: Zuo et al.
conference: Proceedings of the 38th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2025
bibkey: zuo2025value
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.05321'}]
tags: [Training Techniques, Attention Mechanism, Tools, Model Architecture, Reinforcement
    Learning, SIGIR, Fine Tuning]
---
In the realm of sponsored search advertising, matching advertisements with
the search intent of a user's query is crucial. Query-to-bidwords(i.e. bidding
keywords) rewriting is a vital technique that has garnered significant
attention. Recently, with the prevalence of LLMs, generative retrieval methods
have proven effective in producing high-relevance rewrites. However, we have
identified a significant limitation in existing approaches: While fine-tuning
LLMs for specific domains enhances semantic relevance, these models have no
perception of the intrinsic value of their generated outputs, such as
commercial value. Therefore, after SFT, a RLHF phase is often employed to
address this issue. Nevertheless, traditional preference alignment methods
often face challenges in aligning fine-grained values and are susceptible to
overfitting, which diminishes the effectiveness and quality of the generated
results. To address these challenges, we propose VALUE(Value-Aware Large
language model for qUery rewriting via wEighted trie), the first framework that
ensures the generation of high-value and highly relevant bidwords. Our approach
utilizes weighted trie, an innovative modification of the traditional trie data
structure. By modulating the LLM's output probability distribution with value
information from the trie during decoding process, we constrain the generation
space and guide the trajectory of text production. Offline experiments
demonstrate the effectiveness of our method in semantic matching and preference
alignment, showing a remarkable improvement in the value attribute by more than
fivefold. Online A/B tests further revealed that our Revenue Per Mille (RPM)
metric increased by 1.64%. VALUE has been deployed on our advertising system
since October 2024 and served the Double Eleven promotions, the biggest
shopping carnival in China.
---
layout: publication
title: Crosslingual Reasoning Through Test-time Scaling
authors: Yong et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: yong2025crosslingual
citations: 124
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.05408'}]
tags: [ACL, Reinforcement Learning]
---
Reasoning capabilities of large language models are primarily studied for
English, even when pretrained models are multilingual. In this work, we
investigate to what extent English reasoning finetuning with long
chain-of-thoughts (CoTs) can generalize across languages. First, we find that
scaling up inference compute for English-centric reasoning language models
(RLMs) improves multilingual mathematical reasoning across many languages
including low-resource languages, to an extent where they outperform models
twice their size. Second, we reveal that while English-centric RLM's CoTs are
naturally predominantly English, they consistently follow a quote-and-think
pattern to reason about quoted non-English inputs. Third, we discover an
effective strategy to control the language of long CoT reasoning, and we
observe that models reason better and more efficiently in high-resource
languages. Finally, we observe poor out-of-domain reasoning generalization, in
particular from STEM to cultural commonsense knowledge, even for English.
Overall, we demonstrate the potentials, study the mechanisms and outline the
limitations of crosslingual generalization of English reasoning test-time
scaling. We conclude that practitioners should let English-centric RLMs reason
in high-resource languages, while further work is needed to improve reasoning
in low-resource languages and out-of-domain contexts.
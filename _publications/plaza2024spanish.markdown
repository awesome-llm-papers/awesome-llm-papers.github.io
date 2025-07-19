---
layout: publication
title: 'Spanish And LLM Benchmarks: Is MMLU Lost In Translation?'
authors: Plaza et al.
conference: Agricultural Water Management
year: 2024
bibkey: plaza2024spanish
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.17789'}]
tags: [GPT, Evaluation, Model Architecture, Reinforcement Learning, Datasets]
---
The evaluation of Large Language Models (LLMs) is a key element in their
continuous improvement process and many benchmarks have been developed to
assess the performance of LLMs in different tasks and topics. As LLMs become
adopted worldwide, evaluating them in languages other than English is
increasingly important. However, most LLM benchmarks are simply translated
using an automated tool and then run in the target language. This means that
the results depend not only on the LLM performance in that language but also on
the quality of the translation. In this paper, we consider the case of the
well-known Massive Multitask Language Understanding (MMLU) benchmark. Selected
categories of the benchmark are translated into Spanish using Azure Translator
and ChatGPT4 and run on ChatGPT4. Next, the results are processed to identify
the test items that produce different answers in Spanish and English. Those are
then analyzed manually to understand if the automatic translation caused the
change. The results show that a significant fraction of the failing items can
be attributed to mistakes in the translation of the benchmark. These results
make a strong case for improving benchmarks in languages other than English by
at least revising the translations of the items and preferably by adapting the
tests to the target language by experts.
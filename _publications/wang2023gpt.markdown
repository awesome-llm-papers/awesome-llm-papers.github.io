---
layout: publication
title: 'GPT-NER: Named Entity Recognition Via Large Language Models'
authors: Shuhe Wang, Xiaofei Sun, Xiaoya Li, Rongbin Ouyang, Fei Wu, Tianwei Zhang,
  Jiwei Li, Guoyin Wang
conference: Arxiv
year: 2023
bibkey: wang2023gpt
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.10428'}]
tags: ["Applications", "Model Architecture"]
short_authors: Wang et al.
---
Despite the fact that large-scale Language Models (LLM) have achieved SOTA
performances on a variety of NLP tasks, its performance on NER is still
significantly below supervised baselines. This is due to the gap between the
two tasks the NER and LLMs: the former is a sequence labeling task in nature
while the latter is a text-generation model.
  In this paper, we propose GPT-NER to resolve this issue. GPT-NER bridges the
gap by transforming the sequence labeling task to a generation task that can be
easily adapted by LLMs e.g., the task of finding location entities in the input
text "Columbus is a city" is transformed to generate the text sequence
"@@Columbus## is a city", where special tokens @@## marks the entity to
extract. To efficiently address the "hallucination" issue of LLMs, where LLMs
have a strong inclination to over-confidently label NULL inputs as entities, we
propose a self-verification strategy by prompting LLMs to ask itself whether
the extracted entities belong to a labeled entity tag.
  We conduct experiments on five widely adopted NER datasets, and GPT-NER
achieves comparable performances to fully supervised baselines, which is the
first time as far as we are concerned. More importantly, we find that GPT-NER
exhibits a greater ability in the low-resource and few-shot setups, when the
amount of training data is extremely scarce, GPT-NER performs significantly
better than supervised models. This demonstrates the capabilities of GPT-NER in
real-world NER applications where the number of labeled examples is limited.
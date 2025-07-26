---
layout: publication
title: 'Replacing Judges With Juries: Evaluating LLM Generations With A Panel Of Diverse
  Models'
authors: Pat Verga, Sebastian Hofstatter, Sophia Althammer, Yixuan Su, Aleksandra
  Piktus, Arkady Arkhangorodsky, Minjie Xu, Naomi White, Patrick Lewis
conference: No Venue
year: 2024
bibkey: verga2024replacing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.18796'}]
tags: ["Ethics & Fairness"]
short_authors: Verga et al.
---
As Large Language Models (LLMs) have become more advanced, they have outpaced our abilities to accurately evaluate their quality. Not only is finding data to adequately probe particular model properties difficult, but evaluating the correctness of a model's freeform generation alone is a challenge. To address this, many evaluations now rely on using LLMs themselves as judges to score the quality of outputs from other LLMs. Evaluations most commonly use a single large model like GPT4. While this method has grown in popularity, it is costly, has been shown to introduce intramodel bias, and in this work, we find that very large models are often unnecessary. We propose instead to evaluate models using a Panel of LLm evaluators (PoLL). Across three distinct judge settings and spanning six different datasets, we find that using a PoLL composed of a larger number of smaller models outperforms a single large judge, exhibits less intra-model bias due to its composition of disjoint model families, and does so while being over seven times less expensive.

https://huggingface.co/discussions/paper/66305fa2cee11621a131ea08
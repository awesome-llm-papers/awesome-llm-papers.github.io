---
layout: publication
title: Why Does Surprisal From Larger Transformer-based Language Models Provide A
  Poorer Fit To Human Reading Times?
authors: Byung-doh Oh, William Schuler
conference: Transactions of the Association for Computational Linguistics
year: 2022
citations: 36
bibkey: oh2022why
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.12131'}]
tags: [Model Architecture, GPT, Transformer, Reinforcement Learning, Training Techniques]
---
This work presents a detailed linguistic analysis into why larger
Transformer-based pre-trained language models with more parameters and lower
perplexity nonetheless yield surprisal estimates that are less predictive of
human reading times. First, regression analyses show a strictly monotonic,
positive log-linear relationship between perplexity and fit to reading times
for the more recently released five GPT-Neo variants and eight OPT variants on
two separate datasets, replicating earlier results limited to just GPT-2 (Oh et
al., 2022). Subsequently, analysis of residual errors reveals a systematic
deviation of the larger variants, such as underpredicting reading times of
named entities and making compensatory overpredictions for reading times of
function words such as modals and conjunctions. These results suggest that the
propensity of larger Transformer-based models to 'memorize' sequences during
training makes their surprisal estimates diverge from humanlike expectations,
which warrants caution in using pre-trained language models to study human
language processing.
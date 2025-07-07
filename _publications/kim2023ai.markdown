---
layout: publication
title: 'Ai-augmented Surveys: Leveraging Large Language Models And Surveys For Opinion
  Prediction'
authors: Junsol Kim, Byungkyu Lee
conference: Arxiv
year: 2023
citations: 18
bibkey: kim2023ai
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.09620'}]
tags: [Merging, RAG, Tools, Reinforcement Learning, Applications, Survey Paper]
---
Large language models (LLMs) that produce human-like responses have begun to
revolutionize research practices in the social sciences. We develop a novel
methodological framework that fine-tunes LLMs with repeated cross-sectional
surveys to incorporate the meaning of survey questions, individual beliefs, and
temporal contexts for opinion prediction. We introduce two new emerging
applications of the AI-augmented survey: retrodiction (i.e., predict year-level
missing responses) and unasked opinion prediction (i.e., predict entirely
missing responses). Among 3,110 binarized opinions from 68,846 Americans in the
General Social Survey from 1972 to 2021, our models based on Alpaca-7b excel in
retrodiction (AUC = 0.86 for personal opinion prediction, \\(\rho\\) = 0.98 for
public opinion prediction). These remarkable prediction capabilities allow us
to fill in missing trends with high confidence and pinpoint when public
attitudes changed, such as the rising support for same-sex marriage. On the
other hand, our fine-tuned Alpaca-7b models show modest success in unasked
opinion prediction (AUC = 0.73, \\(\rho\\) = 0.67). We discuss practical
constraints and ethical concerns regarding individual autonomy and privacy when
using LLMs for opinion prediction. Our study demonstrates that LLMs and surveys
can mutually enhance each other's capabilities: LLMs can broaden survey
potential, while surveys can improve the alignment of LLMs.
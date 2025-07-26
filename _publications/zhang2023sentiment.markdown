---
layout: publication
title: 'Sentiment Analysis In The Era Of Large Language Models: A Reality Check'
authors: Wenxuan Zhang, Yue Deng, Bing Liu, Sinno Jialin Pan, Lidong Bing
conference: 'Findings of the Association for Computational Linguistics: NAACL 2024'
year: 2024
bibkey: zhang2023sentiment
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.15005'}]
tags: ["Evaluation", "NAACL"]
short_authors: Zhang et al.
---
Sentiment analysis (SA) has been a long-standing research area in natural
language processing. It can offer rich insights into human sentiments and
opinions and has thus seen considerable interest from both academia and
industry. With the advent of large language models (LLMs) such as ChatGPT,
there is a great potential for their employment on SA problems. However, the
extent to which existing LLMs can be leveraged for different sentiment analysis
tasks remains unclear. This paper aims to provide a comprehensive investigation
into the capabilities of LLMs in performing various sentiment analysis tasks,
from conventional sentiment classification to aspect-based sentiment analysis
and multifaceted analysis of subjective texts. We evaluate performance across
13 tasks on 26 datasets and compare the results against small language models
(SLMs) trained on domain-specific datasets. Our study reveals that while LLMs
demonstrate satisfactory performance in simpler tasks, they lag behind in more
complex tasks requiring deeper understanding or structured sentiment
information. However, LLMs significantly outperform SLMs in few-shot learning
settings, suggesting their potential when annotation resources are limited. We
also highlight the limitations of current evaluation practices in assessing
LLMs' SA abilities and propose a novel benchmark, \textsc\{SentiEval\}, for a
more comprehensive and realistic evaluation. Data and code during our
investigations are available at
https://github.com/DAMO-NLP-SG/LLM-Sentiment.
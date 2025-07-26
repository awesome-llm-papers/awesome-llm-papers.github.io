---
layout: publication
title: 'Sadeed: Advancing Arabic Diacritization Through Small Language Model'
authors: Zeina Aldallal, Sara Chrouf, Khalil Hennara, Mohamed Motaism Hamed, Muhammad
  Hreden, Safwan Almodhayan
conference: No Venue
year: 2025
bibkey: aldallal2025sadeed
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68130be65342cbe1ddefb2a6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.21635'}]
tags: ["Applications", "Tools"]
short_authors: Aldallal et al.
---
Arabic text diacritization remains a persistent challenge in natural language processing due to the language's morphological richness. In this paper, we introduce Sadeed, a novel approach based on a fine-tuned decoder-only language model adapted from Kuwain 1.5B Hennara et al. [2025], a compact model originally trained on diverse Arabic corpora. Sadeed is fine-tuned on carefully curated, high-quality diacritized datasets, constructed through a rigorous data-cleaning and normalization pipeline. Despite utilizing modest computational resources, Sadeed achieves competitive results compared to proprietary large language models and outperforms traditional models trained on similar domains. Additionally, we highlight key limitations in current benchmarking practices for Arabic diacritization. To address these issues, we introduce SadeedDiac-25, a new benchmark designed to enable fairer and more comprehensive evaluation across diverse text genres and complexity levels. Together, Sadeed and SadeedDiac-25 provide a robust foundation for advancing Arabic NLP applications, including machine translation, text-to-speech, and language learning tools.

https://huggingface.co/discussions/paper/68130be65342cbe1ddefb2a6
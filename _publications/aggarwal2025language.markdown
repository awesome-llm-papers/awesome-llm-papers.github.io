---
layout: publication
title: Language Models' Factuality Depends On The Language Of Inquiry
authors: Tushar Aggarwal, Kumar Tanmay, Ayush Agrawal, Kumar Ayush, Hamid Palangi,
  Paul Pu Liang
conference: No Venue
year: 2025
bibkey: aggarwal2025language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.17955'}]
tags: ["Evaluation"]
short_authors: Aggarwal et al.
---
Multilingual language models (LMs) are expected to recall factual knowledge consistently across languages, yet they often fail to transfer knowledge between languages even when they possess the correct information in one of the languages. For example, we find that an LM may correctly identify Rashed Al Shashai as being from Saudi Arabia when asked in Arabic, but consistently fails to do so when asked in English or Swahili. To systematically investigate this limitation, we introduce a benchmark of 10,000 country-related facts across 13 languages and propose three novel metrics: Factual Recall Score, Knowledge Transferability Score, and Cross-Lingual Factual Knowledge Transferability Score-to quantify factual recall and knowledge transferability in LMs across different languages. Our results reveal fundamental weaknesses in today's state-of-the-art LMs, particularly in cross-lingual generalization where models fail to transfer knowledge effectively across different languages, leading to inconsistent performance sensitive to the language used. Our findings emphasize the need for LMs to recognize language-specific factual reliability and leverage the most trustworthy information across languages. We release our benchmark and evaluation framework to drive future research in multilingual knowledge transfer.

https://huggingface.co/discussions/paper/67bff528ca6e3c22b6e89ddd
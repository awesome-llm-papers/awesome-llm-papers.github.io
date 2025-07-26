---
layout: publication
title: 'SUTRA: Scalable Multilingual Language Model Architecture'
authors: Abhijit Bendale, Michael Sapienza, Steven Ripplinger, Simon Gibbs, Jaewon
  Lee, Pranav Mistry
conference: No Venue
year: 2024
bibkey: bendale2024sutra
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2405.06694'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Bendale et al.
---
In this paper, we introduce SUTRA, multilingual Large Language Model architecture capable of understanding, reasoning, and generating text in over 50 languages. SUTRA's design uniquely decouples core conceptual understanding from language-specific processing, which facilitates scalable and efficient multilingual alignment and learning. Employing a Mixture of Experts framework both in language and concept processing, SUTRA demonstrates both computational efficiency and responsiveness. Through extensive evaluations, SUTRA is demonstrated to surpass existing models like GPT-3.5, Llama2 by 20-30% on leading Massive Multitask Language Understanding (MMLU) benchmarks for multilingual tasks. SUTRA models are also online LLMs that can use knowledge from the internet to provide hallucination-free, factual and up-to-date responses while retaining their multilingual capabilities. Furthermore, we explore the broader implications of its architecture for the future of multilingual AI, highlighting its potential to democratize access to AI technology globally and to improve the equity and utility of AI in regions with predominantly non-English languages. Our findings suggest that SUTRA not only fills pivotal gaps in multilingual model capabilities but also establishes a new benchmark for operational efficiency and scalability in AI applications.

https://huggingface.co/discussions/paper/6642e575b0c1e83df343d5f5
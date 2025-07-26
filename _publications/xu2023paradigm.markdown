---
layout: publication
title: 'A Paradigm Shift In Machine Translation: Boosting Translation Performance
  Of Large Language Models'
authors: Haoran Xu, Young Jin Kim, Amr Sharaf, Hany Hassan Awadalla
conference: No Venue
year: 2023
bibkey: xu2023paradigm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/650ce69f23e8028a895c626e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2309.11674'}]
tags: ["Datasets", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Xu et al.
---
Generative Large Language Models (LLMs) have achieved remarkable advancements in various NLP tasks. However, these advances have not been reflected in the translation task, especially those with moderate model sizes (i.e., 7B or 13B parameters), which still lag behind conventional supervised encoder-decoder translation models. Previous studies have attempted to improve the translation capabilities of these moderate LLMs, but their gains have been limited. In this study, we propose a novel fine-tuning approach for LLMs that is specifically designed for the translation task, eliminating the need for the abundant parallel data that traditional translation models usually depend on. Our approach consists of two fine-tuning stages: initial fine-tuning on monolingual data followed by subsequent fine-tuning on a small set of high-quality parallel data. We introduce the LLM developed through this strategy as Advanced Language Model-based trAnslator (ALMA). Based on LLaMA-2 as our underlying model, our results show that the model can achieve an average improvement of more than 12 BLEU and 12 COMET over its zero-shot performance across 10 translation directions from the WMT'21 (2 directions) and WMT'22 (8 directions) test datasets. The performance is significantly better than all prior work and even superior to the NLLB-54B model and GPT-3.5-text-davinci-003, with only 7B or 13B parameters. This method establishes the foundation for a novel training paradigm in machine translation.

https://huggingface.co/discussions/paper/650ce69f23e8028a895c626e
---
layout: publication
title: Prompting For Multimodal Hateful Meme Classification
authors: Rui Cao, Roy Ka-wei Lee, Wen-haw Chong, Jing Jiang
conference: Arxiv
year: 2023
citations: 33
bibkey: cao2023prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.04156'}]
tags: [RAG, BERT, Prompting, Multimodal Models, Model Architecture]
---
Hateful meme classification is a challenging multimodal task that requires
complex reasoning and contextual background knowledge. Ideally, we could
leverage an explicit external knowledge base to supplement contextual and
cultural information in hateful memes. However, there is no known explicit
external knowledge base that could provide such hate speech contextual
information. To address this gap, we propose PromptHate, a simple yet effective
prompt-based model that prompts pre-trained language models (PLMs) for hateful
meme classification. Specifically, we construct simple prompts and provide a
few in-context examples to exploit the implicit knowledge in the pre-trained
RoBERTa language model for hateful meme classification. We conduct extensive
experiments on two publicly available hateful and offensive meme datasets. Our
experimental results show that PromptHate is able to achieve a high AUC of
90.96, outperforming state-of-the-art baselines on the hateful meme
classification task. We also perform fine-grained analyses and case studies on
various prompt settings and demonstrate the effectiveness of the prompts on
hateful meme classification.
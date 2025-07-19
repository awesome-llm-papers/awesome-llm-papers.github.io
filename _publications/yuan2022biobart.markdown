---
layout: publication
title: 'Biobart: Pretraining And Evaluation Of A Biomedical Generative Language Model'
authors: Yuan et al.
conference: Proceedings of the 21st Workshop on Biomedical Language Processing
year: 2022
bibkey: yuan2022biobart
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.03905'}]
tags: [Prompting, Training Techniques, Evaluation, Datasets]
---
Pretrained language models have served as important backbones for natural
language processing. Recently, in-domain pretraining has been shown to benefit
various domain-specific downstream tasks. In the biomedical domain, natural
language generation (NLG) tasks are of critical importance, while understudied.
Approaching natural language understanding (NLU) tasks as NLG achieves
satisfying performance in the general domain through constrained language
generation or language prompting. We emphasize the lack of in-domain generative
language models and the unsystematic generative downstream benchmarks in the
biomedical domain, hindering the development of the research community. In this
work, we introduce the generative language model BioBART that adapts BART to
the biomedical domain. We collate various biomedical language generation tasks
including dialogue, summarization, entity linking, and named entity
recognition. BioBART pretrained on PubMed abstracts has enhanced performance
compared to BART and set strong baselines on several tasks. Furthermore, we
conduct ablation studies on the pretraining tasks for BioBART and find that
sentence permutation has negative effects on downstream tasks.
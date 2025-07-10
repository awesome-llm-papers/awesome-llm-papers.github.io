---
layout: publication
title: On Transferability Of Prompt Tuning For Natural Language Processing
authors: Yusheng Su et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
citations: 22
bibkey: su2021transferability
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.06719'}, {name: Code,
    url: 'https://github.com/thunlp/Prompt-Transferability'}]
tags: [Has Code, Fine-Tuning, Reinforcement Learning, Prompting, Efficiency and Optimization,
  Training Techniques]
---
Prompt tuning (PT) is a promising parameter-efficient method to utilize
extremely large pre-trained language models (PLMs), which can achieve
comparable performance to full-parameter fine-tuning by only tuning a few soft
prompts. However, PT requires much more training time than fine-tuning.
Intuitively, knowledge transfer can help to improve the efficiency. To explore
whether we can improve PT via prompt transfer, we empirically investigate the
transferability of soft prompts across different downstream tasks and PLMs in
this work. We find that (1) in zero-shot setting, trained soft prompts can
effectively transfer to similar tasks on the same PLM and also to other PLMs
with a cross-model projector trained on similar tasks; (2) when used as
initialization, trained soft prompts of similar tasks and projected prompts of
other PLMs can significantly accelerate training and also improve the
performance of PT. Moreover, to explore what decides prompt transferability, we
investigate various transferability indicators and find that the overlapping
rate of activated neurons strongly reflects the transferability, which suggests
how the prompts stimulate PLMs is essential. Our findings show that prompt
transfer is promising for improving PT, and further research shall focus more
on prompts' stimulation to PLMs. The source code can be obtained from
https://github.com/thunlp/Prompt-Transferability.
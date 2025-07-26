---
layout: publication
title: Prompt Tuning With Soft Context Sharing For Vision-language Models
authors: Kun Ding, Ying Wang, Pengzhang Liu, Qiang Yu, Haojian Zhang, Shiming Xiang,
  Chunhong Pan
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2022'
year: 2022
bibkey: ding2022prompt
citations: 78
additional_links: [{name: Code, url: 'https://github.com/kding1225/softcpt'}, {name: Paper,
    url: 'https://arxiv.org/abs/2208.13474'}]
tags: ["EMNLP", "Prompting", "Training Techniques"]
short_authors: Ding et al.
---
Vision-language models have recently shown great potential on many tasks in
computer vision. Meanwhile, prior work demonstrates prompt tuning designed for
vision-language models could acquire superior performance on few-shot image
recognition compared to linear probe, a strong baseline. In practice, many
few-shot tasks are inherently correlated, particularly within specialized
domains. However, such information is overlooked previously. Inspired by the
fact that modeling task relationship by multi-task learning can usually boost
performance, we propose a novel method SoftCPT (Soft Context Sharing for Prompt
Tuning) to tune pre-trained vision-language models on multiple target few-shot
tasks jointly. Specifically, we design a task-shared meta network to generate
prompt context for each task using task name together with a learnable task
context as input. The parameters of this meta network as well as the task
context are tuned on the joint training set of all tasks. As such, the prompt
context of all tasks will be shared in a soft manner. Extensive experiments
across four multi-task few-shot datasets covering 44 tasks and 1593 categories
demonstrate that SoftCPT significantly outperforms single-task prompt tuning
methods, highlighting the effectiveness of multi-task learning for
vision-language prompt tuning. Code is available at
https://github.com/kding1225/softcpt.
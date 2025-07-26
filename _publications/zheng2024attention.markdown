---
layout: publication
title: 'Attention Heads Of Large Language Models: A Survey'
authors: Zifan Zheng, Yezhaohui Wang, Yuxin Huang, Shichao Song, Bo Tang, Feiyu Xiong,
  Zhiyu Li
conference: No Venue
year: 2024
bibkey: zheng2024attention
additional_links: [{name: Code, url: 'https://github.com/IAAR-Shanghai/Awesome-Attention-Heads'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.03752'}]
tags: ["Model Architecture", "Survey Paper"]
short_authors: Zheng et al.
---
Since the advent of ChatGPT, Large Language Models (LLMs) have excelled in various tasks but remain largely as black-box systems. Consequently, their development relies heavily on data-driven approaches, limiting performance enhancement through changes in internal architecture and reasoning pathways. As a result, many researchers have begun exploring the potential internal mechanisms of LLMs, aiming to identify the essence of their reasoning bottlenecks, with most studies focusing on attention heads. Our survey aims to shed light on the internal reasoning processes of LLMs by concentrating on the interpretability and underlying mechanisms of attention heads. We first distill the human thought process into a four-stage framework: Knowledge Recalling, In-Context Identification, Latent Reasoning, and Expression Preparation. Using this framework, we systematically review existing research to identify and categorize the functions of specific attention heads. Furthermore, we summarize the experimental methodologies used to discover these special heads, dividing them into two categories: Modeling-Free methods and Modeling-Required methods. Also, we outline relevant evaluation methods and benchmarks. Finally, we discuss the limitations of current research and propose several potential future directions. Our reference list is open-sourced at https://github.com/IAAR-Shanghai/Awesome-Attention-Heads.

https://huggingface.co/discussions/paper/66da5f1a247166c36547fd62
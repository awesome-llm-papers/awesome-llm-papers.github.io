---
layout: publication
title: 'Distillm-2: A Contrastive Approach Boosts The Distillation Of Llms'
authors: Jongwoo Ko, Tianyi Chen, Sungnyun Kim, Tianyu Ding, Luming Liang, Ilya Zharkov,
  Se-young Yun
conference: No Venue
year: 2025
bibkey: ko2025distillm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67cfa99c7c95194db8d754bf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.07067'}]
tags: ["Efficiency"]
short_authors: Ko et al.
---
Despite the success of distillation in large language models (LLMs), most prior work applies identical loss functions to both teacher- and student-generated data. These strategies overlook the synergy between loss formulations and data types, leading to a suboptimal performance boost in student models. To address this, we propose DistiLLM-2, a contrastive approach that simultaneously increases the likelihood of teacher responses and decreases that of student responses by harnessing this synergy. Our extensive experiments show that DistiLLM-2 not only builds high-performing student models across a wide range of tasks, including instruction-following and code generation, but also supports diverse applications, such as preference alignment and vision-language extensions. These findings highlight the potential of a contrastive approach to enhance the efficacy of LLM distillation by effectively aligning teacher and student models across varied data types.

https://huggingface.co/discussions/paper/67cfa99c7c95194db8d754bf
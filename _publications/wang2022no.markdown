---
layout: publication
title: No More Fine-tuning? An Experimental Evaluation Of Prompt Tuning In Code Intelligence
authors: Chaozheng Wang, Yuanhang Yang, Cuiyun Gao, Yun Peng, Hongyu Zhang, Michael
  R. Lyu
conference: Proceedings of the 30th ACM Joint European Software Engineering Conference
  and Symposium on the Foundations of Software Engineering
year: 2022
bibkey: wang2022no
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.11680'}]
tags: ["Evaluation", "Fine-Tuning", "Llm For Code", "Prompting", "Training Techniques"]
short_authors: Wang et al.
---
Pre-trained models have been shown effective in many code intelligence tasks.
These models are pre-trained on large-scale unlabeled corpus and then
fine-tuned in downstream tasks. However, as the inputs to pre-training and
downstream tasks are in different forms, it is hard to fully explore the
knowledge of pre-trained models. Besides, the performance of fine-tuning
strongly relies on the amount of downstream data, while in practice, the
scenarios with scarce data are common. Recent studies in the natural language
processing (NLP) field show that prompt tuning, a new paradigm for tuning,
alleviates the above issues and achieves promising results in various NLP
tasks. In prompt tuning, the prompts inserted during tuning provide
task-specific knowledge, which is especially beneficial for tasks with
relatively scarce data. In this paper, we empirically evaluate the usage and
effect of prompt tuning in code intelligence tasks. We conduct prompt tuning on
popular pre-trained models CodeBERT and CodeT5 and experiment with three code
intelligence tasks including defect prediction, code summarization, and code
translation. Our experimental results show that prompt tuning consistently
outperforms fine-tuning in all three tasks. In addition, prompt tuning shows
great potential in low-resource scenarios, e.g., improving the BLEU scores of
fine-tuning by more than 26% on average for code summarization. Our results
suggest that instead of fine-tuning, we could adapt prompt tuning for code
intelligence tasks to achieve better performance, especially when lacking
task-specific data.
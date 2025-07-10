---
layout: publication
title: 'Bioinstruct: Instruction Tuning Of Large Language Models For Biomedical Natural
  Language Processing'
authors: Hieu Tran, Zhichao Yang, Zonghai Yao, Hong Yu
conference: Journal of the American Medical Informatics Association
year: 2023
citations: 17
bibkey: tran2023instruction
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.19975'}]
tags: [Model Architecture, GPT, Fine-Tuning, Applications, Prompting, Training Techniques]
---
To enhance the performance of large language models (LLMs) in biomedical
natural language processing (BioNLP) by introducing a domain-specific
instruction dataset and examining its impact when combined with multi-task
learning principles. We created the BioInstruct, comprising 25,005 instructions
to instruction-tune LLMs(LLaMA 1 & 2, 7B & 13B version). The instructions were
created by prompting the GPT-4 language model with three-seed samples randomly
drawn from an 80 human curated instructions. We employed Low-Rank
Adaptation(LoRA) for parameter-efficient fine-tuning. We then evaluated these
instruction-tuned LLMs on several BioNLP tasks, which can be grouped into three
major categories: question answering(QA), information extraction(IE), and text
generation(GEN). We also examined whether categories(e.g., QA, IE, and
generation) of instructions impact model performance. Comparing with LLMs
without instruction-tuned, our instruction-tuned LLMs demonstrated marked
performance gains: 17.3% in QA, 5.7% in IE, and 96% in Generation tasks. Our
7B-parameter instruction-tuned LLaMA 1 model was competitive or even surpassed
other LLMs in the biomedical domain that were also fine-tuned from LLaMA 1 with
vast domain-specific data or a variety of tasks. Our results also show that the
performance gain is significantly higher when instruction fine-tuning is
conducted with closely related tasks. Our findings align with the observations
of multi-task learning, suggesting the synergies between two tasks. The
BioInstruct dataset serves as a valuable resource and instruction tuned LLMs
lead to the best performing BioNLP applications.
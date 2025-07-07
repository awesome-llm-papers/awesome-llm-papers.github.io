---
layout: publication
title: 'Mental-llm: Leveraging Large Language Models For Mental Health Prediction
  Via Online Text Data'
authors: Xuhai Xu et al.
conference: Arxiv
year: 2023
citations: 33
bibkey: xu2023mental
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.14385'}]
tags: [Ethics and Bias, Training Techniques, GPT, RAG, Few-Shot, Reinforcement Learning,
  Fine-Tuning, In-Context Learning, Applications, Prompting, Model Architecture]
---
Advances in large language models (LLMs) have empowered a variety of
applications. However, there is still a significant gap in research when it
comes to understanding and enhancing the capabilities of LLMs in the field of
mental health. In this work, we present a comprehensive evaluation of multiple
LLMs on various mental health prediction tasks via online text data, including
Alpaca, Alpaca-LoRA, FLAN-T5, GPT-3.5, and GPT-4. We conduct a broad range of
experiments, covering zero-shot prompting, few-shot prompting, and instruction
fine-tuning. The results indicate a promising yet limited performance of LLMs
with zero-shot and few-shot prompt designs for mental health tasks. More
importantly, our experiments show that instruction finetuning can significantly
boost the performance of LLMs for all tasks simultaneously. Our best-finetuned
models, Mental-Alpaca and Mental-FLAN-T5, outperform the best prompt design of
GPT-3.5 (25 and 15 times bigger) by 10.9% on balanced accuracy and the best of
GPT-4 (250 and 150 times bigger) by 4.8%. They further perform on par with the
state-of-the-art task-specific language model. We also conduct an exploratory
case study on LLMs' capability on mental health reasoning tasks, illustrating
the promising capability of certain models such as GPT-4. We summarize our
findings into a set of action guidelines for potential methods to enhance LLMs'
capability for mental health tasks. Meanwhile, we also emphasize the important
limitations before achieving deployability in real-world mental health
settings, such as known racial and gender bias. We highlight the important
ethical risks accompanying this line of research.
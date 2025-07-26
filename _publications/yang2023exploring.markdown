---
layout: publication
title: Exploring An LM To Generate Prolog Predicates From Mathematics Questions
authors: Xiaocheng Yang, Yik-cheung Tam
conference: Arxiv
year: 2023
bibkey: yang2023exploring
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.03667'}]
tags: ["Fine-Tuning", "Model Architecture", "Prompting"]
short_authors: Xiaocheng Yang, Yik-cheung Tam
---
Recently, there has been a surge in interest in NLP driven by ChatGPT.
ChatGPT, a transformer-based generative language model of substantial scale,
exhibits versatility in performing various tasks based on natural language.
Nevertheless, large language models often exhibit poor performance in solving
mathematics questions that require reasoning. Prior research has demonstrated
the effectiveness of chain-of-thought prompting in enhancing reasoning
capabilities. Now, we aim to investigate whether fine-tuning a model for the
generation of Prolog codes, a logic language, and subsequently passing these
codes to a compiler can further improve accuracy. Consequently, we employ
chain-of-thought to fine-tune LLaMA7B as a baseline model and develop other
fine-tuned LLaMA7B models for the generation of Prolog code, Prolog code +
chain-of-thought, and chain-of-thought + Prolog code, respectively. The results
reveal that the Prolog generation model surpasses the baseline in performance,
while the combination generation models do not yield significant improvements.
The Prolog corpus based on GSM8K and the correspondingly finetuned Prolog
generation model based on LLaMA7B are released to the research community.
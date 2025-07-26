---
layout: publication
title: Patent Claim Generation By Fine-tuning Openai GPT-2
authors: Jieh-sheng Lee, Jieh Hsiang
conference: World Patent Information
year: 2020
bibkey: lee2019patent
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.02052'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Jieh-sheng Lee, Jieh Hsiang
---
In this work, we focus on fine-tuning an OpenAI GPT-2 pre-trained model for
generating patent claims. GPT-2 has demonstrated impressive efficacy of
pre-trained language models on various tasks, particularly coherent text
generation. Patent claim language itself has rarely been explored in the past
and poses a unique challenge. We are motivated to generate coherent patent
claims automatically so that augmented inventing might be viable someday. In
our implementation, we identified a unique language structure in patent claims
and leveraged its implicit human annotations. We investigated the fine-tuning
process by probing the first 100 steps and observing the generated text at each
step. Based on both conditional and unconditional random sampling, we analyze
the overall quality of generated patent claims. Our contributions include: (1)
being the first to generate patent claims by machines and being the first to
apply GPT-2 to patent claim generation, (2) providing various experiment
results for qualitative analysis and future research, (3) proposing a new
sampling approach for text generation, and (4) building an e-mail bot for
future researchers to explore the fine-tuned GPT-2 model further.
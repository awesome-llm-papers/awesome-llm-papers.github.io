---
layout: publication
title: How Much Knowledge Can You Pack Into A Lora Adapter Without Harming LLM?
authors: Sergey Pletenev, Maria Marina, Daniil Moskovskiy, Vasily Konovalov, Pavel
  Braslavski, Alexander Panchenko, Mikhail Salnikov
conference: No Venue
year: 2025
bibkey: pletenev2025how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.14502'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Pletenev et al.
---
The performance of Large Language Models (LLMs) on many tasks is greatly limited by the knowledge learned during pre-training and stored in the model's parameters. Low-rank adaptation (LoRA) is a popular and efficient training technique for updating or domain-specific adaptation of LLMs. In this study, we investigate how new facts can be incorporated into the LLM using LoRA without compromising the previously learned knowledge. We fine-tuned Llama-3.1-8B-instruct using LoRA with varying amounts of new knowledge. Our experiments have shown that the best results are obtained when the training data contains a mixture of known and new facts. However, this approach is still potentially harmful because the model's performance on external question-answering benchmarks declines after such fine-tuning. When the training data is biased towards certain entities, the model tends to regress to few overrepresented answers. In addition, we found that the model becomes more confident and refuses to provide an answer in only few cases. These findings highlight the potential pitfalls of LoRA-based LLM updates and underscore the importance of training data composition and tuning parameters to balance new knowledge integration and general model capabilities.

https://huggingface.co/discussions/paper/67b83fd79fb3eedaf6d0af16
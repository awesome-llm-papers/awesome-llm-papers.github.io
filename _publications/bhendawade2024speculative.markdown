---
layout: publication
title: 'Speculative Streaming: Fast LLM Inference Without Auxiliary Models'
authors: Nikhil Bhendawade, Irina Belousova, Qichen Fu, Henry Mason, Mohammad Rastegari,
  Mahyar Najibi
conference: No Venue
year: 2024
bibkey: bhendawade2024speculative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.11131'}]
tags: ["Fine-Tuning"]
short_authors: Bhendawade et al.
---
Speculative decoding is a prominent technique to speed up the inference of a large target language model based on predictions of an auxiliary draft model. While effective, in application-specific settings, it often involves fine-tuning both draft and target models to achieve high acceptance rates. As the number of downstream tasks grows, these draft models add significant complexity to inference systems. We propose Speculative Streaming, a single-model speculative decoding method that fuses drafting into the target model by changing the fine-tuning objective from next token prediction to future n-gram prediction. Speculative Streaming speeds up decoding by 1.8 - 3.1X in a diverse set of tasks, such as Summarization, Structured Queries, and Meaning Representation, without sacrificing generation quality. Additionally, Speculative Streaming is parameter-efficient. It achieves on-par/higher speed-ups than Medusa-style architectures while using ~10000X fewer extra parameters, making it well-suited for resource-constrained devices.

https://huggingface.co/discussions/paper/65d438720cf70a406c627749
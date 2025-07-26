---
layout: publication
title: Lora Learns Less And Forgets Less
authors: Dan Biderman, Jose Gonzalez Ortiz, Jacob Portes, Mansheej Paul, Philip Greengard,
  Connor Jennings, Daniel King, Sam Havens, Vitaliy Chiley, Jonathan Frankle, Cody
  Blakeney, John P. Cunningham
conference: No Venue
year: 2024
bibkey: biderman2024lora
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6646bb309d3a5b2ddb400d76'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.09673'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Biderman et al.
---
Low-Rank Adaptation (LoRA) is a widely-used parameter-efficient finetuning method for large language models. LoRA saves memory by training only low rank perturbations to selected weight matrices. In this work, we compare the performance of LoRA and full finetuning on two target domains, programming and mathematics. We consider both the instruction finetuning (approx100K prompt-response pairs) and continued pretraining (approx10B unstructured tokens) data regimes. Our results show that, in most settings, LoRA substantially underperforms full finetuning. Nevertheless, LoRA exhibits a desirable form of regularization: it better maintains the base model's performance on tasks outside the target domain. We show that LoRA provides stronger regularization compared to common techniques such as weight decay and dropout; it also helps maintain more diverse generations. We show that full finetuning learns perturbations with a rank that is 10-100X greater than typical LoRA configurations, possibly explaining some of the reported gaps. We conclude by proposing best practices for finetuning with LoRA.

https://huggingface.co/discussions/paper/6646bb309d3a5b2ddb400d76
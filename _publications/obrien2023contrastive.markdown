---
layout: publication
title: Contrastive Decoding Improves Reasoning In Large Language Models
authors: Sean O'brien, Mike Lewis
conference: No Venue
year: 2023
bibkey: obrien2023contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.09117'}]
tags: ["Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Sean O'brien, Mike Lewis
---
We demonstrate that Contrastive Decoding -- a simple, computationally light, and training-free text generation method proposed by Li et al 2022 -- achieves large out-of-the-box improvements over greedy decoding on a variety of reasoning tasks. Originally shown to improve the perceived quality of long-form text generation, Contrastive Decoding searches for strings that maximize a weighted difference in likelihood between strong and weak models. We show that Contrastive Decoding leads LLaMA-65B to outperform LLaMA 2, GPT-3.5 and PaLM 2-L on the HellaSwag commonsense reasoning benchmark, and to outperform LLaMA 2, GPT-3.5 and PaLM-540B on the GSM8K math word reasoning benchmark, in addition to improvements on a collection of other tasks. Analysis suggests that Contrastive Decoding improves over existing methods by preventing some abstract reasoning errors, as well as by avoiding simpler modes such as copying sections of the input during chain-of-thought. Overall, Contrastive Decoding outperforms nucleus sampling for long-form generation and greedy decoding for reasoning tasks, making it a powerful general purpose method for generating text from language models.

https://huggingface.co/discussions/paper/65090e377ee07e274b2618cd
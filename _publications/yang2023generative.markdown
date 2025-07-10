---
layout: publication
title: Generative Speech Recognition Error Correction With Large Language Models And
  Task-activating Prompting
authors: Chao-han Huck Yang et al.
conference: 2023 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2023
citations: 17
bibkey: yang2023generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.15649'}]
tags: [Fine-Tuning, Few-Shot, ACL, In-Context Learning, Prompting, Training Techniques,
  INTERSPEECH]
---
We explore the ability of large language models (LLMs) to act as speech
recognition post-processors that perform rescoring and error correction. Our
first focus is on instruction prompting to let LLMs perform these task without
fine-tuning, for which we evaluate different prompting schemes, both zero- and
few-shot in-context learning, and a novel task activation prompting method that
combines causal instructions and demonstration to increase its context windows.
Next, we show that rescoring only by in-context learning with frozen LLMs
achieves results that are competitive with rescoring by domain-tuned LMs, using
a pretrained first-pass recognition system and rescoring output on two
out-of-domain tasks (ATIS and WSJ). By combining prompting techniques with
fine-tuning we achieve error rates below the N-best oracle level, showcasing
the generalization power of the LLMs.
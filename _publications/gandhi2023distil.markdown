---
layout: publication
title: 'Distil-whisper: Robust Knowledge Distillation Via Large-scale Pseudo Labelling'
authors: Sanchit Gandhi, Patrick von Platen, Alexander M. Rush
conference: No Venue
year: 2023
bibkey: gandhi2023distil
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65430c769ce0fa3dfa3c1ed9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2311.00430'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Sanchit Gandhi, Patrick von Platen, Alexander M. Rush
---
As the size of pre-trained speech recognition models increases, running these large models in low-latency or resource-constrained environments becomes challenging. In this work, we leverage pseudo-labelling to assemble a large-scale open-source dataset which we use to distill the Whisper model into a smaller variant, called Distil-Whisper. Using a simple word error rate (WER) heuristic, we select only the highest quality pseudo-labels for training. The distilled model is 5.8 times faster with 51% fewer parameters, while performing to within 1% WER on out-of-distribution test data in a zero-shot transfer setting. Distil-Whisper maintains the robustness of the Whisper model to difficult acoustic conditions, while being less prone to hallucination errors on long-form audio. Distil-Whisper is designed to be paired with Whisper for speculative decoding, yielding a 2 times speed-up while mathematically ensuring the same outputs as the original model. To facilitate further research in this domain, we make our training code, inference code and models publicly accessible.

https://huggingface.co/discussions/paper/65430c769ce0fa3dfa3c1ed9
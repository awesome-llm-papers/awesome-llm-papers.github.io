---
layout: publication
title: 'LLM Pruning And Distillation In Practice: The Minitron Approach'
authors: Sharath Turuvekere Sreenivas, Saurav Muralidharan, Raviraj Joshi, Marcin
  Chochowski, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro, Jan Kautz, Pavlo
  Molchanov
conference: No Venue
year: 2024
bibkey: sreenivas2024llm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66c6c724e8e0c0e0a2cafd7a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.11796'}]
tags: ["Efficiency"]
short_authors: Sreenivas et al.
---
We present a comprehensive report on compressing the Llama 3.1 8B and Mistral NeMo 12B models to 4B and 8B parameters, respectively, using pruning and distillation. We explore two distinct pruning strategies: (1) depth pruning and (2) joint hidden/attention/MLP (width) pruning, and evaluate the results on common benchmarks from the LM Evaluation Harness. The models are then aligned with NeMo Aligner and tested in instruct-tuned versions. This approach produces a compelling 4B model from Llama 3.1 8B and a state-of-the-art Mistral-NeMo-Minitron-8B (MN-Minitron-8B for brevity) model from Mistral NeMo 12B. We found that with no access to the original data, it is beneficial to slightly fine-tune teacher models on the distillation dataset. We open-source our base model weights on Hugging Face with a permissive license.

https://huggingface.co/discussions/paper/66c6c724e8e0c0e0a2cafd7a
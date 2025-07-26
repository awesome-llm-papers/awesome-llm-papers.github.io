---
layout: publication
title: Pixtral 12B
authors: "Pravesh Agrawal, Szymon Antoniak, Emma Bou Hanna, Devendra Chaplot, Jessica\
  \ Chudnovsky, Saurabh Garg, Theophile Gervet, Soham Ghosh, Am\xE9lie H\xE9liou,\
  \ Paul Jacob, Albert Q. Jiang, Timoth\xE9e Lacroix, Guillaume Lample, Diego Las\
  \ Casas, Thibaut Lavril, Teven Le Scao, Andy Lo, William Marshall, Louis Martin,\
  \ Arthur Mensch, Pavankumar Muddireddy, Valera Nemychnikova, Marie Pellat, Patrick\
  \ von Platen, Nikhil Raghuraman, Baptiste Rozi\xE8re, Alexandre Sablayrolles, Lucile\
  \ Saulnier, Romain Sauvestre, Wendy Shang, Roman Soletskyi, Lawrence Stewart, Pierre\
  \ Stock, Joachim Studnia, Sandeep Subramanian, Sagar Vaze, Thomas Wang"
conference: No Venue
year: 2024
bibkey: agrawal2024pixtral
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/670746f33e510db7639042b6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.07073'}]
tags: ["Evaluation", "Memory & Context"]
short_authors: Agrawal et al.
---
We introduce Pixtral-12B, a 12--billion-parameter multimodal language model. Pixtral-12B is trained to understand both natural images and documents, achieving leading performance on various multimodal benchmarks, surpassing a number of larger models. Unlike many open-source models, Pixtral is also a cutting-edge text model for its size, and does not compromise on natural language performance to excel in multimodal tasks. Pixtral uses a new vision encoder trained from scratch, which allows it to ingest images at their natural resolution and aspect ratio. This gives users flexibility on the number of tokens used to process an image. Pixtral is also able to process any number of images in its long context window of 128K tokens. Pixtral 12B substanially outperforms other open models of similar sizes (Llama-3.2 11B \& Qwen-2-VL 7B). It also outperforms much larger open models like Llama-3.2 90B while being 7x smaller. We further contribute an open-source benchmark, MM-MT-Bench, for evaluating vision-language models in practical scenarios, and provide detailed analysis and code for standardized evaluation protocols for multimodal LLMs. Pixtral-12B is released under Apache 2.0 license.

https://huggingface.co/discussions/paper/670746f33e510db7639042b6
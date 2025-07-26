---
layout: publication
title: 'Olmoe: Open Mixture-of-experts Language Models'
authors: Niklas Muennighoff, Luca Soldaini, Dirk Groeneveld, Kyle Lo, Jacob Morrison,
  Sewon Min, Weijia Shi, Pete Walsh, Oyvind Tafjord, Nathan Lambert, Yuling Gu, Shane
  Arora, Akshita Bhagia, Dustin Schwenk, David Wadden, Alexander Wettig, Binyuan Hui,
  Tim Dettmers, Douwe Kiela, Ali Farhadi, Noah A. Smith, Pang Wei Koh, Amanpreet Singh,
  Hannaneh Hajishirzi
conference: No Venue
year: 2024
bibkey: muennighoff2024olmoe
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66d7c910e1aee6b7145bd73a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.02060'}]
tags: ["Training Techniques"]
short_authors: Muennighoff et al.
---
We introduce OLMoE, a fully open, state-of-the-art language model leveraging sparse Mixture-of-Experts (MoE). OLMoE-1B-7B has 7 billion (B) parameters but uses only 1B per input token. We pretrain it on 5 trillion tokens and further adapt it to create OLMoE-1B-7B-Instruct. Our models outperform all available models with similar active parameters, even surpassing larger ones like Llama2-13B-Chat and DeepSeekMoE-16B. We present various experiments on MoE training, analyze routing in our model showing high specialization, and open-source all aspects of our work: model weights, training data, code, and logs.

https://huggingface.co/discussions/paper/66d7c910e1aee6b7145bd73a
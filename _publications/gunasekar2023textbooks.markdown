---
layout: publication
title: Textbooks Are All You Need
authors: "Suriya Gunasekar, Yi Zhang, Jyoti Aneja, Caio C\xE9sar Teodoro Mendes, Allie\
  \ del Giorno, Sivakanth Gopi, Mojan Javaheripi, Piero Kauffmann, Gustavo de Rosa,\
  \ Olli Saarikivi, Adil Salim, Shital Shah, Harkirat Singh Behl, Xin Wang, S\xE9\
  bastien Bubeck, Ronen Eldan, Adam Tauman Kalai, Yin Tat Lee, Yuanzhi Li"
conference: No Venue
year: 2023
bibkey: gunasekar2023textbooks
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/64926f45ef19676db9353fb1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2306.11644'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Gunasekar et al.
---
We introduce phi-1, a new large language model for code, with significantly smaller size than competing models: phi-1 is a Transformer-based model with 1.3B parameters, trained for 4 days on 8 A100s, using a selection of ``textbook quality" data from the web (6B tokens) and synthetically generated textbooks and exercises with GPT-3.5 (1B tokens). Despite this small scale, phi-1 attains pass@1 accuracy 50.6% on HumanEval and 55.5% on MBPP. It also displays surprising emergent properties compared to phi-1-base, our model before our finetuning stage on a dataset of coding exercises, and phi-1-small, a smaller model with 350M parameters trained with the same pipeline as phi-1 that still achieves 45% on HumanEval.

https://huggingface.co/discussions/paper/64926f45ef19676db9353fb1
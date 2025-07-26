---
layout: publication
title: 'Synthdetoxm: Modern Llms Are Few-shot Parallel Detoxification Data Annotators'
authors: Daniil Moskovskiy, Nikita Sushko, Sergey Pletenev, Elena Tutubalina, Alexander
  Panchenko
conference: No Venue
year: 2025
bibkey: moskovskiy2025synthdetoxm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67aafeae3711ca5b760f3280'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.06394'}]
tags: ["Evaluation", "Few-Shot"]
short_authors: Moskovskiy et al.
---
Existing approaches to multilingual text detoxification are hampered by the scarcity of parallel multilingual datasets. In this work, we introduce a pipeline for the generation of multilingual parallel detoxification data. We also introduce SynthDetoxM, a manually collected and synthetically generated multilingual parallel text detoxification dataset comprising 16,000 high-quality detoxification sentence pairs across German, French, Spanish and Russian. The data was sourced from different toxicity evaluation datasets and then rewritten with nine modern open-source LLMs in few-shot setting. Our experiments demonstrate that models trained on the produced synthetic datasets have superior performance to those trained on the human-annotated MultiParaDetox dataset even in data limited setting. Models trained on SynthDetoxM outperform all evaluated LLMs in few-shot setting. We release our dataset and code to help further research in multilingual text detoxification.

https://huggingface.co/discussions/paper/67aafeae3711ca5b760f3280
---
layout: publication
title: 'Openthoughts: Data Recipes For Reasoning Models'
authors: Etash Guha, Ryan Marten, Sedrick Keh, Negin Raoof, Georgios Smyrnis, Hritik
  Bansal, Marianna Nezhurina, Jean Mercat, Trung Vu, Zayne Sprague, Ashima Suvarna,
  Benjamin Feuer, Liangyu Chen, Zaid Khan, Eric Frankel, Sachin Grover, Caroline Choi,
  Niklas Muennighoff, Shiye Su, Wanjia Zhao, John Yang, Shreyas Pimpalgaonkar, Kartik
  Sharma, Charlie Cheng-jie Ji, Yichuan Deng, Sarah Pratt, Vivek Ramanujan, Jon Saad-falcon,
  Jeffrey Li, Achal Dave, Alon Albalak, Kushal Arora, Blake Wulfe, Chinmay Hegde,
  Greg Durrett, Sewoong Oh, Mohit Bansal, Saadia Gabriel, Aditya Grover, Kai-wei Chang,
  Vaishaal Shankar, Aaron Gokaslan, Mike A. Merrill, Tatsunori Hashimoto, Yejin Choi,
  Jenia Jitsev, Reinhard Heckel, Maheswaran Sathiamoorthy, Alexandros G. Dimakis,
  Ludwig Schmidt
conference: No Venue
year: 2025
bibkey: guha2025openthoughts
additional_links: [{name: Code, url: 'https://openthoughts.ai'}, {name: Code, url: 'https://huggingface.co/discussions/paper/68417763d777f13c594dd0af'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.04178'}]
tags: ["Datasets"]
short_authors: Guha et al.
---
Reasoning models have made rapid progress on many benchmarks involving math, code, and science. Yet, there are still many open questions about the best training recipes for reasoning since state-of-the-art models often rely on proprietary datasets with little to no public information available. To address this, the goal of the OpenThoughts project is to create open-source datasets for training reasoning models. After initial explorations, our OpenThoughts2-1M dataset led to OpenThinker2-32B, the first model trained on public reasoning data to match DeepSeek-R1-Distill-32B on standard reasoning benchmarks such as AIME and LiveCodeBench. We then improve our dataset further by systematically investigating each step of our data generation pipeline with 1,000+ controlled experiments, which led to OpenThoughts3. Scaling the pipeline to 1.2M examples and using QwQ-32B as teacher yields our OpenThinker3-7B model, which achieves state-of-the-art results: 53% on AIME 2025, 51% on LiveCodeBench 06/24-01/25, and 54% on GPQA Diamond. All of our datasets and models are available on https://openthoughts.ai.

https://huggingface.co/discussions/paper/68417763d777f13c594dd0af
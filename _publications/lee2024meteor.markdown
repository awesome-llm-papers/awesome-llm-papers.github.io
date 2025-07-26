---
layout: publication
title: 'Meteor: Mamba-based Traversal Of Rationale For Large Language And Vision Models'
authors: Byung-kwan Lee, Chae Won Kim, Beomchan Park, Yong Man Ro
conference: No Venue
year: 2024
bibkey: lee2024meteor
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6653f0c8607894ea80484b7a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.15574'}]
tags: ["Model Architecture"]
short_authors: Lee et al.
---
The rapid development of large language and vision models (LLVMs) has been driven by advances in visual instruction tuning. Recently, open-source LLVMs have curated high-quality visual instruction tuning datasets and utilized additional vision encoders or multiple computer vision models in order to narrow the performance gap with powerful closed-source LLVMs. These advancements are attributed to multifaceted information required for diverse capabilities, including fundamental image understanding, real-world knowledge about common-sense and non-object concepts (e.g., charts, diagrams, symbols, signs, and math problems), and step-by-step procedures for solving complex questions. Drawing from the multifaceted information, we present a new efficient LLVM, Mamba-based traversal of rationales (Meteor), which leverages multifaceted rationale to enhance understanding and answering capabilities. To embed lengthy rationales containing abundant information, we employ the Mamba architecture, capable of processing sequential data with linear time complexity. We introduce a new concept of traversal of rationale that facilitates efficient embedding of rationale. Subsequently, the backbone multimodal language model (MLM) is trained to generate answers with the aid of rationale. Through these steps, Meteor achieves significant improvements in vision language performances across multiple evaluation benchmarks requiring diverse capabilities, without scaling up the model size or employing additional vision encoders and computer vision models.

https://huggingface.co/discussions/paper/6653f0c8607894ea80484b7a
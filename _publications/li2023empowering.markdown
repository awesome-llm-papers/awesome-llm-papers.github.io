---
layout: publication
title: 'Empowering Molecule Discovery For Molecule-caption Translation With Large
  Language Models: A Chatgpt Perspective'
authors: Jiatong Li et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2023
citations: 18
bibkey: li2023empowering
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.06615'}]
tags: [Model Architecture, GPT, Fine-Tuning, RAG, Few-Shot, Applications, Tools, Reinforcement
    Learning, Multimodal Models, Pre-Training, In-Context Learning, Training Techniques]
---
Molecule discovery plays a crucial role in various scientific fields,
advancing the design of tailored materials and drugs. However, most of the
existing methods heavily rely on domain experts, require excessive
computational cost, or suffer from sub-optimal performance. On the other hand,
Large Language Models (LLMs), like ChatGPT, have shown remarkable performance
in various cross-modal tasks due to their powerful capabilities in natural
language understanding, generalization, and in-context learning (ICL), which
provides unprecedented opportunities to advance molecule discovery. Despite
several previous works trying to apply LLMs in this task, the lack of
domain-specific corpus and difficulties in training specialized LLMs still
remain challenges. In this work, we propose a novel LLM-based framework
(MolReGPT) for molecule-caption translation, where an In-Context Few-Shot
Molecule Learning paradigm is introduced to empower molecule discovery with
LLMs like ChatGPT to perform their in-context learning capability without
domain-specific pre-training and fine-tuning. MolReGPT leverages the principle
of molecular similarity to retrieve similar molecules and their text
descriptions from a local database to enable LLMs to learn the task knowledge
from context examples. We evaluate the effectiveness of MolReGPT on
molecule-caption translation, including molecule understanding and text-based
molecule generation. Experimental results show that compared to fine-tuned
models, MolReGPT outperforms MolT5-base and is comparable to MolT5-large
without additional training. To the best of our knowledge, MolReGPT is the
first work to leverage LLMs via in-context learning in molecule-caption
translation for advancing molecule discovery. Our work expands the scope of LLM
applications, as well as providing a new paradigm for molecule discovery and
design.
---
layout: publication
title: Conceptnet Infused Dialogpt For Underlying Commonsense Understanding And Reasoning
  In Dialogue Response Generation
authors: Liu et al.
conference: BT Technology Journal
year: 2022
bibkey: liu2022conceptnet
citations: 864
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.15109'}]
tags: [RAG, Training Techniques, GPT, Agentic, Model Architecture, Reinforcement Learning,
  Datasets, Merging]
---
The pre-trained conversational models still fail to capture the implicit
commonsense (CS) knowledge hidden in the dialogue interaction, even though they
were pre-trained with an enormous dataset. In order to build a dialogue agent
with CS capability, we firstly inject external knowledge into a pre-trained
conversational model to establish basic commonsense through efficient Adapter
tuning (Section 4). Secondly, we propose the ``two-way learning'' method to
enable the bidirectional relationship between CS knowledge and sentence pairs
so that the model can generate a sentence given the CS triplets, also generate
the underlying CS knowledge given a sentence (Section 5). Finally, we leverage
this integrated CS capability to improve open-domain dialogue response
generation so that the dialogue agent is capable of understanding the CS
knowledge hidden in dialogue history on top of inferring related other
knowledge to further guide response generation (Section 6). The experiment
results demonstrate that CS\_Adapter fusion helps DialoGPT to be able to
generate series of CS knowledge. And the DialoGPT+CS\_Adapter response model
adapted from CommonGen training can generate underlying CS triplets that fits
better to dialogue context.
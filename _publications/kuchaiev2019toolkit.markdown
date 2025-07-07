---
layout: publication
title: 'Nemo: A Toolkit For Building AI Applications Using Neural Modules'
authors: Oleksii Kuchaiev et al.
conference: Arxiv
year: 2019
citations: 162
bibkey: kuchaiev2019toolkit
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.09577'}, {name: Code,
    url: 'https://github.com/NVIDIA/NeMo'}]
tags: [Large-Scale Training, Training Techniques, INTERSPEECH, Reinforcement Learning,
  Tools, Has Code, Applications]
---
NeMo (Neural Modules) is a Python framework-agnostic toolkit for creating AI
applications through re-usability, abstraction, and composition. NeMo is built
around neural modules, conceptual blocks of neural networks that take typed
inputs and produce typed outputs. Such modules typically represent data layers,
encoders, decoders, language models, loss functions, or methods of combining
activations. NeMo makes it easy to combine and re-use these building blocks
while providing a level of semantic correctness checking via its neural type
system. The toolkit comes with extendable collections of pre-built modules for
automatic speech recognition and natural language processing. Furthermore, NeMo
provides built-in support for distributed training and mixed precision on
latest NVIDIA GPUs. NeMo is open-source https://github.com/NVIDIA/NeMo
---
layout: publication
title: 'Nemo: A Toolkit For Building AI Applications Using Neural Modules'
authors: Oleksii Kuchaiev, Jason Li, Huyen Nguyen, Oleksii Hrinchuk, Ryan Leary, Boris
  Ginsburg, Samuel Kriman, Stanislav Beliaev, Vitaly Lavrukhin, Jack Cook, Patrice
  Castonguay, Mariya Popova, Jocelyn Huang, Jonathan M. Cohen
conference: Arxiv
year: 2019
bibkey: kuchaiev2019nemo
citations: 164
additional_links: [{name: Code, url: 'https://github.com/NVIDIA/NeMo'}, {name: Paper,
    url: 'https://arxiv.org/abs/1909.09577'}]
tags: ["Applications", "Has Code", "Tools"]
short_authors: Kuchaiev et al.
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
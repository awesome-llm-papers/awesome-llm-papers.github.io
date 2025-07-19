---
layout: publication
title: 'Torchfl: A Performant Library For Bootstrapping Federated Learning Experiments'
authors: Khimani Vivek, Jabbari Shahin
conference: Proceedings 2021 Network and Distributed System Security Symposium
year: 2022
bibkey: khimani2022torchfl
citations: 432
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.00735'}]
tags: [Agentic, Tools, Model Architecture, Reinforcement Learning, Security, Datasets]
---
With the increased legislation around data privacy, federated learning (FL)
has emerged as a promising technique that allows the clients (end-user) to
collaboratively train deep learning (DL) models without transferring and
storing the data in a centralized, third-party server. We introduce TorchFL, a
performant library for (i) bootstrapping the FL experiments, (ii) executing
them using various hardware accelerators, (iii) profiling the performance, and
(iv) logging the overall and agent-specific results on the go. Being built on a
bottom-up design using PyTorch and Lightning, TorchFL provides ready-to-use
abstractions for models, datasets, and FL algorithms, while allowing the
developers to customize them as and when required. This paper aims to dig
deeper into the architecture and design of TorchFL, elaborate on how it allows
researchers to bootstrap the federated learning experience, and provide
experiments and code snippets for the same. With the ready-to-use
implementation of state-of-the-art DL models, datasets, and federated learning
support, TorchFL aims to allow researchers with little to no engineering
background to set up FL experiments with minimal coding and infrastructure
overhead.
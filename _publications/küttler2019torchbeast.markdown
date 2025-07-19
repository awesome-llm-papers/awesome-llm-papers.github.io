---
layout: publication
title: 'Torchbeast: A Pytorch Platform For Distributed RL'
authors: "K\xFCttler et al."
conference: Proceedings of the VLDB Endowment
year: 2019
bibkey: "k\xFCttler2019torchbeast"
citations: 290
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.03552'}]
tags: [Agentic, Tools, Training Techniques, Reinforcement Learning]
---
TorchBeast is a platform for reinforcement learning (RL) research in PyTorch.
It implements a version of the popular IMPALA algorithm for fast, asynchronous,
parallel training of RL agents. Additionally, TorchBeast has simplicity as an
explicit design goal: We provide both a pure-Python implementation
("MonoBeast") as well as a multi-machine high-performance version
("PolyBeast"). In the latter, parts of the implementation are written in C++,
but all parts pertaining to machine learning are kept in simple Python using
PyTorch, with the environments provided using the OpenAI Gym interface. This
enables researchers to conduct scalable RL research using TorchBeast without
any programming knowledge beyond Python and PyTorch. In this paper, we describe
the TorchBeast design principles and implementation and demonstrate that it
performs on-par with IMPALA on Atari. TorchBeast is released as an open-source
package under the Apache 2.0 license and is available at
https://github.com/facebookresearch/torchbeast.
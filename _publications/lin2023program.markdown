---
layout: publication
title: 'Program Machine Policy: Addressing Long-horizon Tasks By Integrating Program
  Synthesis And State Machines'
authors: Lin et al.
conference: Journal of Parallel and Distributed Computing
year: 2023
bibkey: lin2023program
citations: 320
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.15960'}]
tags: [Interpretability And Explainability, RAG, Training Techniques, Agentic, Tools,
  Reinforcement Learning, Fine Tuning]
---
Deep reinforcement learning (deep RL) excels in various domains but lacks
generalizability and interpretability. On the other hand, programmatic RL
methods (Trivedi et al., 2021; Liu et al., 2023) reformulate RL tasks as
synthesizing interpretable programs that can be executed in the environments.
Despite encouraging results, these methods are limited to short-horizon tasks.
On the other hand, representing RL policies using state machines (Inala et al.,
2020) can inductively generalize to long-horizon tasks; however, it struggles
to scale up to acquire diverse and complex behaviors. This work proposes the
Program Machine Policy (POMP), which bridges the advantages of programmatic RL
and state machine policies, allowing for the representation of complex
behaviors and the address of long-term tasks. Specifically, we introduce a
method that can retrieve a set of effective, diverse, and compatible programs.
Then, we use these programs as modes of a state machine and learn a transition
function to transition among mode programs, allowing for capturing repetitive
behaviors. Our proposed framework outperforms programmatic RL and deep RL
baselines on various tasks and demonstrates the ability to inductively
generalize to even longer horizons without any fine-tuning. Ablation studies
justify the effectiveness of our proposed search algorithm for retrieving a set
of programs as modes.
---
layout: publication
title: 'Programming By Backprop: Llms Acquire Reusable Algorithmic Abstractions During
  Code Training'
authors: Cook et al.
conference: Proceedings 2003 IEEE/RSJ International Conference on Intelligent Robots
  and Systems (IROS 2003) (Cat. No.03CH37453)
year: 2025
bibkey: cook2025programming
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.18777'}]
tags: [Training Techniques, Reinforcement Learning, Evaluation, IROS]
---
Training large language models (LLMs) on source code significantly enhances their general-purpose reasoning abilities, but the mechanisms underlying this generalisation are poorly understood. In this paper, we propose Programming by Backprop (PBB) as a potential driver of this effect - teaching a model to evaluate a program for inputs by training on its source code alone, without ever seeing I/O examples. To explore this idea, we finetune LLMs on two sets of programs representing simple maths problems and algorithms: one with source code and I/O examples (w/ IO), the other with source code only (w/o IO). We find evidence that LLMs have some ability to evaluate w/o IO programs for inputs in a range of experimental settings, and make several observations. Firstly, PBB works significantly better when programs are provided as code rather than semantically equivalent language descriptions. Secondly, LLMs can produce outputs for w/o IO programs directly, by implicitly evaluating the program within the forward pass, and more reliably when stepping through the program in-context via chain-of-thought. We further show that PBB leads to more robust evaluation of programs across inputs than training on I/O pairs drawn from a distribution that mirrors naturally occurring data. Our findings suggest a mechanism for enhanced reasoning through code training: it allows LLMs to internalise reusable algorithmic abstractions. Significant scope remains for future work to enable LLMs to more effectively learn from symbolic procedures, and progress in this direction opens other avenues like model alignment by training on formal constitutional principles.
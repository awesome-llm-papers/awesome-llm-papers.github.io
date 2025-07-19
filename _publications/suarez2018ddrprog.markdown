---
layout: publication
title: 'Ddrprog: A CLEVR Differentiable Dynamic Reasoning Programmer'
authors: Suarez Joseph, Johnson Justin, Li Fei-fei
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2018
bibkey: suarez2018ddrprog
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.11361'}]
tags: [RAG, Tools, Evaluation, CVPR, Model Architecture, Reinforcement Learning]
---
We present a novel Dynamic Differentiable Reasoning (DDR) framework for
jointly learning branching programs and the functions composing them; this
resolves a significant nondifferentiability inhibiting recent dynamic
architectures. We apply our framework to two settings in two highly compact and
data efficient architectures: DDRprog for CLEVR Visual Question Answering and
DDRstack for reverse Polish notation expression evaluation. DDRprog uses a
recurrent controller to jointly predict and execute modular neural programs
that directly correspond to the underlying question logic; it explicitly forks
subprocesses to handle logical branching. By effectively leveraging additional
structural supervision, we achieve a large improvement over previous approaches
in subtask consistency and a small improvement in overall accuracy. We further
demonstrate the benefits of structural supervision in the RPN setting: the
inclusion of a stack assumption in DDRstack allows our approach to generalize
to long expressions where an LSTM fails the task.
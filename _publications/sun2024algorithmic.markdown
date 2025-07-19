---
layout: publication
title: 'Algorithmic Phase Transitions In Language Models: A Mechanistic Case Study
  Of Arithmetic'
authors: Sun Alan, Sun Ethan, Shepard Warren
conference: 2008 49th Annual IEEE Symposium on Foundations of Computer Science
year: 2024
bibkey: sun2024algorithmic
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.07386'}]
tags: [Tools, Training Techniques]
---
Zero-shot capabilities of large language models make them powerful tools for
solving a range of tasks without explicit training. It remains unclear,
however, how these models achieve such performance, or why they can zero-shot
some tasks but not others. In this paper, we shed some light on this phenomenon
by defining and investigating algorithmic stability in language models --
changes in problem-solving strategy employed by the model as a result of
changes in task specification. We focus on a task where algorithmic stability
is needed for generalization: two-operand arithmetic. Surprisingly, we find
that Gemma-2-2b employs substantially different computational models on closely
related subtasks, i.e. four-digit versus eight-digit addition. Our findings
suggest that algorithmic instability may be a contributing factor to language
models' poor zero-shot performance across certain logical reasoning tasks, as
they struggle to abstract different problem-solving strategies and smoothly
transition between them.
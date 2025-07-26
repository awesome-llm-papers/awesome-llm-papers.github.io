---
layout: publication
title: 'Numglue: A Suite Of Fundamental Yet Challenging Mathematical Reasoning Tasks'
authors: Swaroop Mishra, Arindam Mitra, Neeraj Varshney, Bhavdeep Sachdeva, Peter
  Clark, Chitta Baral, Ashwin Kalyan
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: mishra2022numglue
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.05660'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Mishra et al.
---
Given the ubiquitous nature of numbers in text, reasoning with numbers to
perform simple calculations is an important skill of AI systems. While many
datasets and models have been developed to this end, state-of-the-art AI
systems are brittle; failing to perform the underlying mathematical reasoning
when they appear in a slightly different scenario. Drawing inspiration from
GLUE that was proposed in the context of natural language understanding, we
propose NumGLUE, a multi-task benchmark that evaluates the performance of AI
systems on eight different tasks, that at their core require simple arithmetic
understanding. We show that this benchmark is far from being solved with neural
models including state-of-the-art large-scale language models performing
significantly worse than humans (lower by 46.4%). Further, NumGLUE promotes
sharing knowledge across tasks, especially those with limited training data as
evidenced by the superior performance (average gain of 3.4% on each task) when
a model is jointly trained on all the tasks as opposed to task-specific
modeling. Finally, we hope that NumGLUE will encourage systems that perform
robust and general arithmetic reasoning within language, a first step towards
being able to perform more complex mathematical reasoning.
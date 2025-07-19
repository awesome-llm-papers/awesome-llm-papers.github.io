---
layout: publication
title: 'Bwarea Model: Learning World Model, Inverse Dynamics, And Policy For Controllable
  Language Generation'
authors: Jia et al.
conference: 2010 IEEE International Conference on Robotics and Automation
year: 2024
bibkey: jia2024bwarea
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.17039'}]
tags: [ICRA, Training Techniques, Evaluation, Reinforcement Learning, Applications,
  Fine Tuning]
---
Large language models (LLMs) have catalyzed a paradigm shift in natural
language processing, yet their limited controllability poses a significant
challenge for downstream applications. We aim to address this by drawing
inspiration from the neural mechanisms of the human brain, specifically Broca's
and Wernicke's areas, which are crucial for language generation and
comprehension, respectively. In particular, Broca's area receives cognitive
decision signals from Wernicke's area, treating the language generation as an
intricate decision-making process, which differs from the fully auto-regressive
language generation of existing LLMs. In a similar vein, our proposed system,
the BWArea model, conceptualizes language generation as a decision-making task.
This model has three components: a language world model, an inverse dynamics
model, and a cognitive policy. Like Wernicke's area, the inverse dynamics model
is designed to deduce the underlying cognitive intentions, or latent actions,
behind each token. The BWArea model is amenable to both pre-training and
fine-tuning like existing LLMs. With 30B clean pre-training tokens, we have
trained a BWArea model, which achieves competitive performance with LLMs of
equal size (1B parameters). Unlike fully auto-regressive LLMs, its pre-training
performance does not degenerate if dirty data unintentionally appears. This
shows the advantage of a decomposed structure of BWArea model in reducing
efforts in laborious data selection and labeling. Finally, we reveal that the
BWArea model offers enhanced controllability via fine-tuning the cognitive
policy with downstream reward metrics, thereby facilitating alignment with
greater simplicity. On 9 out of 10 tasks from two suites, TextWorld and
BigBench Hard, our method shows superior performance to auto-regressive LLMs.
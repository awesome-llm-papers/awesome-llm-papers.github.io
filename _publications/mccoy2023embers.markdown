---
layout: publication
title: 'Embers Of Autoregression: Understanding Large Language Models Through The
  Problem They Are Trained To Solve'
authors: R. Thomas Mccoy, Shunyu Yao, Dan Friedman, Matthew Hardy, Thomas L. Griffiths
conference: Arxiv
year: 2023
citations: 26
bibkey: mccoy2023embers
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.13638'}]
tags: [GPT, Model Architecture]
---
The widespread adoption of large language models (LLMs) makes it important to
recognize their strengths and limitations. We argue that in order to develop a
holistic understanding of these systems we need to consider the problem that
they were trained to solve: next-word prediction over Internet text. By
recognizing the pressures that this task exerts we can make predictions about
the strategies that LLMs will adopt, allowing us to reason about when they will
succeed or fail. This approach - which we call the teleological approach -
leads us to identify three factors that we hypothesize will influence LLM
accuracy: the probability of the task to be performed, the probability of the
target output, and the probability of the provided input. We predict that LLMs
will achieve higher accuracy when these probabilities are high than when they
are low - even in deterministic settings where probability should not matter.
To test our predictions, we evaluate two LLMs (GPT-3.5 and GPT-4) on eleven
tasks, and we find robust evidence that LLMs are influenced by probability in
the ways that we have hypothesized. In many cases, the experiments reveal
surprising failure modes. For instance, GPT-4's accuracy at decoding a simple
cipher is 51% when the output is a high-probability word sequence but only 13%
when it is low-probability. These results show that AI practitioners should be
careful about using LLMs in low-probability situations. More broadly, we
conclude that we should not evaluate LLMs as if they are humans but should
instead treat them as a distinct type of system - one that has been shaped by
its own particular set of pressures.
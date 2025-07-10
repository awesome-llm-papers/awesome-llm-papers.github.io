---
layout: publication
title: 'Analogy Generation By Prompting Large Language Models: A Case Study Of Instructgpt'
authors: Bhavya Bhavya, Jinjun Xiong, Chengxiang Zhai
conference: Proceedings of the 15th International Conference on Natural Language Generation
year: 2022
citations: 18
bibkey: bhavya2022analogy
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.04186'}]
tags: [Model Architecture, Interpretability and Explainability, Reinforcement Learning,
  Prompting, GPT, Evaluation]
---
We propose a novel application of prompting Pre-trained Language Models
(PLMs) to generate analogies and study how to design effective prompts for two
task settings: generating a source concept analogous to a given target concept
(aka Analogous Concept Generation or ACG), and generating an explanation of the
similarity between a given pair of target concept and source concept (aka
Analogous Explanation Generation or AEG). We found that it is feasible to
prompt InstructGPT to generate meaningful analogies and the best prompts tend
to be precise imperative statements especially with a low temperature setting.
We also systematically analyzed the sensitivity of the InstructGPT model to
prompt design, temperature, and injected spelling errors, and found that the
model is particularly sensitive to certain variations (e.g., questions vs.
imperative statements). Further, we conducted human evaluation on 1.4k of the
generated analogies and found that the quality of generations varies
substantially by model size. The largest InstructGPT model can achieve
human-level performance at generating meaningful analogies for a given target
while there is still room for improvement on the AEG task.
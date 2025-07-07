---
layout: publication
title: 'Learning How To Ask: Querying Lms With Mixtures Of Soft Prompts'
authors: Guanghui Qin, Jason Eisner
conference: NAACL-HLT 2021
year: 2021
citations: 122
bibkey: qin2021learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.06599'}]
tags: [Training Techniques, Fine-Tuning, Few-Shot, Reinforcement Learning, Prompting]
---
Natural-language prompts have recently been used to coax pretrained language
models into performing other AI tasks, using a fill-in-the-blank paradigm
(Petroni et al., 2019) or a few-shot extrapolation paradigm (Brown et al.,
2020). For example, language models retain factual knowledge from their
training corpora that can be extracted by asking them to "fill in the blank" in
a sentential prompt. However, where does this prompt come from? We explore the
idea of learning prompts by gradient descent -- either fine-tuning prompts
taken from previous work, or starting from random initialization. Our prompts
consist of "soft words," i.e., continuous vectors that are not necessarily word
type embeddings from the language model. Furthermore, for each task, we
optimize a mixture of prompts, learning which prompts are most effective and
how to ensemble them. Across multiple English LMs and tasks, our approach
hugely outperforms previous methods, showing that the implicit factual
knowledge in language models was previously underestimated. Moreover, this
knowledge is cheap to elicit: random initialization is nearly as good as
informed initialization.
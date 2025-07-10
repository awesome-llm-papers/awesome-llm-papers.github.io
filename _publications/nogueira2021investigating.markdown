---
layout: publication
title: Investigating The Limitations Of Transformers With Simple Arithmetic Tasks
authors: Rodrigo Nogueira, Zhiying Jiang, Jimmy Lin
conference: Arxiv
year: 2021
citations: 30
bibkey: nogueira2021investigating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.13019'}, {name: Code,
    url: 'https://github.com/castorini/transformers-arithmetic'}]
tags: [Transformer, Training Techniques, Has Code, Model Architecture]
---
The ability to perform arithmetic tasks is a remarkable trait of human
intelligence and might form a critical component of more complex reasoning
tasks. In this work, we investigate if the surface form of a number has any
influence on how sequence-to-sequence language models learn simple arithmetic
tasks such as addition and subtraction across a wide range of values. We find
that how a number is represented in its surface form has a strong influence on
the model's accuracy. In particular, the model fails to learn addition of
five-digit numbers when using subwords (e.g., "32"), and it struggles to learn
with character-level representations (e.g., "3 2"). By introducing position
tokens (e.g., "3 10e1 2"), the model learns to accurately add and subtract
numbers up to 60 digits. We conclude that modern pretrained language models can
easily learn arithmetic from very few examples, as long as we use the proper
surface representation. This result bolsters evidence that subword tokenizers
and positional encodings are components in current transformer designs that
might need improvement. Moreover, we show that regardless of the number of
parameters and training examples, models cannot learn addition rules that are
independent of the length of the numbers seen during training. Code to
reproduce our experiments is available at
https://github.com/castorini/transformers-arithmetic
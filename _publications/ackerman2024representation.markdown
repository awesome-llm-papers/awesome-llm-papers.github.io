---
layout: publication
title: Representation Tuning
authors: Ackerman Christopher M.
conference: Journal of Neurophysiology
year: 2024
bibkey: ackerman2024representation
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.06927'}]
tags: [Fine Tuning, Prompting, Training Techniques, Responsible AI]
---
Activation engineering is becoming increasingly popular as a means of online
control of large language models (LLMs). In this work, we extend the idea of
inference-time steering with vectors that represent a behavioral direction of
interest to tuning those vectors directly into the model, obviating the need
for online control. First, we identify activation vectors related to honesty in
an open-source LLM (Llama-2-13b-chat). Next, we demonstrate that model output
can be made more or less honest by adding positive or negative multiples of
these vectors to residual stream activations during generation. Then, we show
that a similar effect can be achieved by fine-tuning the vectors directly into
the model, by use of a dual loss function based on the cosine similarity of
residual stream activations to the vectors combined with a standard token-based
loss ("representation tuning"). Finally, we compare the generations in response
to honesty-probing prompts from the resulting models to those from models
fine-tuned with a token-based loss alone, and to those from the untuned model
subjected to online steering. Overall, fine-tuning the vectors into the models
using the cosine similarity plus token loss showed a stronger effect than
online steering, and generalized better than using the standard loss,
suggesting the potential utility of this approach as a safety measure. Code and
data are available at https://github.com/cma1114/representation_tuning. Tuned
models are available at
https://huggingface.co/collections/cackerman/representation-tuning-66da1e5ab41cd1b824687d9f.
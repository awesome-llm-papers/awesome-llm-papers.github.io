---
layout: publication
title: 'How To Evaluate Your Dialogue System: Probe Tasks As An Alternative For Token-level
  Evaluation Metrics'
authors: Parthasarathi Prasanna, Pineau Joelle, Chandar Sarath
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2020
bibkey: parthasarathi2020how
citations: 332
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.10427'}]
tags: [Model Architecture, Evaluation, Agentic, EMNLP, Transformer, Reinforcement
    Learning, Language Modeling, Alt]
---
Though generative dialogue modeling is widely seen as a language modeling
task, the task demands an agent to have a complex natural language
understanding of its input text to carry a meaningful interaction with an user.
The automatic metrics used evaluate the quality of the generated text as a
proxy to the holistic interaction of the agent. Such metrics were earlier shown
to not correlate with the human judgement. In this work, we observe that human
evaluation of dialogue agents can be inconclusive due to the lack of sufficient
information for appropriate evaluation. The automatic metrics are deterministic
yet shallow and human evaluation can be relevant yet inconclusive. To bridge
this gap in evaluation, we propose designing a set of probing tasks to evaluate
dialogue models. The hand-crafted tasks are aimed at quantitatively evaluating
a generative dialogue model's understanding beyond the token-level evaluation
on the generated text. The probing tasks are deterministic like automatic
metrics and requires human judgement in their designing; benefiting from the
best of both worlds. With experiments on probe tasks we observe that, unlike
RNN based architectures, transformer model may not be learning to comprehend
the input text despite its generated text having higher overlap with the target
text.
---
layout: publication
title: Explaining Question Answering Models Through Text Generation
authors: Latcinnik Veronica, Berant Jonathan
conference: Arxiv
year: 2020
bibkey: latcinnik2020explaining
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.05569'}]
tags: [RAG, Training Techniques, Model Architecture, Language Modeling, Reinforcement
    Learning]
---
Large pre-trained language models (LMs) have been shown to perform
surprisingly well when fine-tuned on tasks that require commonsense and world
knowledge. However, in end-to-end architectures, it is difficult to explain
what is the knowledge in the LM that allows it to make a correct prediction. In
this work, we propose a model for multi-choice question answering, where a
LM-based generator generates a textual hypothesis that is later used by a
classifier to answer the question. The hypothesis provides a window into the
information used by the fine-tuned LM that can be inspected by humans. A key
challenge in this setup is how to constrain the model to generate hypotheses
that are meaningful to humans. We tackle this by (a) joint training with a
simple similarity classifier that encourages meaningful hypotheses, and (b) by
adding loss functions that encourage natural text without repetitions. We show
on several tasks that our model reaches performance that is comparable to
end-to-end architectures, while producing hypotheses that elucidate the
knowledge used by the LM for answering the question.
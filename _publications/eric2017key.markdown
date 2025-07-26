---
layout: publication
title: Key-value Retrieval Networks For Task-oriented Dialogue
authors: Mihail Eric, Christopher D. Manning
conference: Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue
year: 2017
bibkey: eric2017key
citations: 398
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.05414'}]
tags: ["Model Architecture"]
short_authors: Mihail Eric, Christopher D. Manning
---
Neural task-oriented dialogue systems often struggle to smoothly interface
with a knowledge base. In this work, we seek to address this problem by
proposing a new neural dialogue agent that is able to effectively sustain
grounded, multi-domain discourse through a novel key-value retrieval mechanism.
The model is end-to-end differentiable and does not need to explicitly model
dialogue state or belief trackers. We also release a new dataset of 3,031
dialogues that are grounded through underlying knowledge bases and span three
distinct tasks in the in-car personal assistant space: calendar scheduling,
weather information retrieval, and point-of-interest navigation. Our
architecture is simultaneously trained on data from all domains and
significantly outperforms a competitive rule-based system and other existing
neural dialogue architectures on the provided domains according to both
automatic and human evaluation metrics.
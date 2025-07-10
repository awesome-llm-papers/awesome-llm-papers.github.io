---
layout: publication
title: Are We Pretraining It Right? Digging Deeper Into Visio-linguistic Pretraining
authors: Amanpreet Singh, Vedanuj Goswami, Devi Parikh
conference: Arxiv
year: 2020
citations: 31
bibkey: singh2020are
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08744'}]
tags: [Training Techniques, Model Architecture, Attention Mechanism]
---
Numerous recent works have proposed pretraining generic visio-linguistic
representations and then finetuning them for downstream vision and language
tasks. While architecture and objective function design choices have received
attention, the choice of pretraining datasets has received little attention. In
this work, we question some of the default choices made in literature. For
instance, we systematically study how varying similarity between the
pretraining dataset domain (textual and visual) and the downstream domain
affects performance. Surprisingly, we show that automatically generated data in
a domain closer to the downstream task (e.g., VQA v2) is a better choice for
pretraining than "natural" data but of a slightly different domain (e.g.,
Conceptual Captions). On the other hand, some seemingly reasonable choices of
pretraining datasets were found to be entirely ineffective for some downstream
tasks. This suggests that despite the numerous recent efforts, vision &
language pretraining does not quite work "out of the box" yet. Overall, as a
by-product of our study, we find that simple design choices in pretraining can
help us achieve close to state-of-art results on downstream tasks without any
architectural changes.
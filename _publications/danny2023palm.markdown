---
layout: publication
title: 'Palm-e: An Embodied Multimodal Language Model'
authors: [danny Driess, fei Xia, mehdi S. M. Sajjadi, corey Lynch, aakanksha Chowdhery,
  brian Ichter, ayzaan Wahid, jonathan Tompson, quan Vuong, tianhe Yu, wenlong Huang,
  yevgen Chebotar, pierre Sermanet, daniel Duckworth, sergey Levine, vincent Vanhoucke,
  karol Hausman, marc Toussaint, klaus Greff, andy Zeng, igor Mordatch, pete Florence]
conference: Arxiv
year: 2023
bibkey: danny2023palm
citations: 299
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2303.03378v1'}]
tags: ["Training Techniques"]
short_authors: Driess et al.
---
Large language models excel at a wide range of complex tasks. However,
enabling general inference in the real world, e.g., for robotics problems,
raises the challenge of grounding. We propose embodied language models to
directly incorporate real-world continuous sensor modalities into language
models and thereby establish the link between words and percepts. Input to our
embodied language model are multi-modal sentences that interleave visual,
continuous state estimation, and textual input encodings. We train these
encodings end-to-end, in conjunction with a pre-trained large language model,
for multiple embodied tasks including sequential robotic manipulation planning,
visual question answering, and captioning. Our evaluations show that PaLM-E, a
single large embodied multimodal model, can address a variety of embodied
reasoning tasks, from a variety of observation modalities, on multiple
embodiments, and further, exhibits positive transfer: the model benefits from
diverse joint training across internet-scale language, vision, and
visual-language domains. Our largest model, PaLM-E-562B with 562B parameters,
in addition to being trained on robotics tasks, is a visual-language generalist
with state-of-the-art performance on OK-VQA, and retains generalist language
capabilities with increasing scale.
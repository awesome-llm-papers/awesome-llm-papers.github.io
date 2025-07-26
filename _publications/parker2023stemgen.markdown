---
layout: publication
title: 'Stemgen: A Music Generation Model That Listens'
authors: Julian D. Parker, Janne Spijkervet, Katerina Kosta, Furkan Yesiler, Boris
  Kuznetsov, Ju-chiang Wang, Matt Avent, Jitong Chen, Duc Le
conference: No Venue
year: 2023
bibkey: parker2023stemgen
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2312.08723'}]
tags: ["Datasets", "Evaluation", "Model Architecture"]
short_authors: Parker et al.
---
End-to-end generation of musical audio using deep learning techniques has seen an explosion of activity recently. However, most models concentrate on generating fully mixed music in response to abstract conditioning information. In this work, we present an alternative paradigm for producing music generation models that can listen and respond to musical context. We describe how such a model can be constructed using a non-autoregressive, transformer-based model architecture and present a number of novel architectural and sampling improvements. We train the described architecture on both an open-source and a proprietary dataset. We evaluate the produced models using standard quality metrics and a new approach based on music information retrieval descriptors. The resulting model reaches the audio quality of state-of-the-art text-conditioned models, as well as exhibiting strong musical coherence with its context.

https://huggingface.co/discussions/paper/657bd8f11fa4e4e152c127b1
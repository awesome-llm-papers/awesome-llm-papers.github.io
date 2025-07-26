---
layout: publication
title: 'Make It Count: Text-to-image Generation With An Accurate Number Of Objects'
authors: Lital Binyamin, Yoad Tewel, Hilit Segev, Eran Hirsch, Royi Rassin, Gal Chechik
conference: No Venue
year: 2024
bibkey: binyamin2024make
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.10210'}]
tags: ["Applications", "Evaluation"]
short_authors: Binyamin et al.
---
Despite the unprecedented success of text-to-image diffusion models, controlling the number of depicted objects using text is surprisingly hard. This is important for various applications from technical documents, to children's books to illustrating cooking recipes. Generating object-correct counts is fundamentally challenging because the generative model needs to keep a sense of separate identity for every instance of the object, even if several objects look identical or overlap, and then carry out a global computation implicitly during generation. It is still unknown if such representations exist. To address count-correct generation, we first identify features within the diffusion model that can carry the object identity information. We then use them to separate and count instances of objects during the denoising process and detect over-generation and under-generation. We fix the latter by training a model that predicts both the shape and location of a missing object, based on the layout of existing ones, and show how it can be used to guide denoising with correct object count. Our approach, CountGen, does not depend on external source to determine object layout, but rather uses the prior from the diffusion model itself, creating prompt-dependent and seed-dependent layouts. Evaluated on two benchmark datasets, we find that CountGen strongly outperforms the count-accuracy of existing baselines.

https://huggingface.co/discussions/paper/666fe1d7b955b0e6551b1a7a
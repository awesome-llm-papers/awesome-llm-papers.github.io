---
layout: publication
title: 'Adv-bert: BERT Is Not Robust On Misspellings! Generating Nature Adversarial
  Samples On BERT'
authors: Lichao Sun, Kazuma Hashimoto, Wenpeng Yin, Akari Asai, Jia Li, Philip Yu,
  Caiming Xiong
conference: Arxiv
year: 2020
bibkey: sun2020adv
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.04985'}]
tags: ["Model Architecture"]
short_authors: Sun et al.
---
There is an increasing amount of literature that claims the brittleness of
deep neural networks in dealing with adversarial examples that are created
maliciously. It is unclear, however, how the models will perform in realistic
scenarios where \textit\{natural rather than malicious\} adversarial instances
often exist. This work systematically explores the robustness of BERT, the
state-of-the-art Transformer-style model in NLP, in dealing with noisy data,
particularly mistakes in typing the keyboard, that occur inadvertently.
Intensive experiments on sentiment analysis and question answering benchmarks
indicate that: (i) Typos in various words of a sentence do not influence
equally. The typos in informative words make severer damages; (ii) Mistype is
the most damaging factor, compared with inserting, deleting, etc.; (iii) Humans
and machines have different focuses on recognizing adversarial attacks.
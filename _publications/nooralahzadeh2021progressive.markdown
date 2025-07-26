---
layout: publication
title: Progressive Transformer-based Generation Of Radiology Reports
authors: Farhad Nooralahzadeh, Nicolas Perez Gonzalez, Thomas Frauenfelder, Koji Fujimoto,
  Michael Krauthammer
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2021
bibkey: nooralahzadeh2021progressive
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.09777'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Nooralahzadeh et al.
---
Inspired by Curriculum Learning, we propose a consecutive (i.e.,
image-to-text-to-text) generation framework where we divide the problem of
radiology report generation into two steps. Contrary to generating the full
radiology report from the image at once, the model generates global concepts
from the image in the first step and then reforms them into finer and coherent
texts using a transformer architecture. We follow the transformer-based
sequence-to-sequence paradigm at each step. We improve upon the
state-of-the-art on two benchmark datasets.